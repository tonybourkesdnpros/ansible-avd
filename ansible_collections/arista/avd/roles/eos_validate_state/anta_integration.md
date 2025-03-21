---
# This title is used for search results
title: Ansible Collection Role eos_validate_state - Integration with ANTA
---
<!--
  ~ Copyright (c) 2023-2024 Arista Networks, Inc.
  ~ Use of this source code is governed by the Apache License 2.0
  ~ that can be found in the LICENSE file.
  -->

# eos_validate_state - Integration with ANTA

!!! note
    [ANTA](https://anta.arista.com/stable/) will be the future default framework leveraged by AVD for network testing and validation. Since it introduces small [breaking changes](#breaking-changes), you have to opt-in to leverage ANTA with `eos_validate_state` by configuring: `use_anta: true`.

# Overview

**eos_validate_state** is a role leveraged to validate Arista EOS devices' operational states.

**eos_validate_state** role:

- Consumes structured EOS configuration file, the same input as the role [eos_cli_config_gen](../eos_cli_config_gen/README.md). This input is considered the system of record (the desired state).
- Connects to EOS devices to collect operational states (actual state). This requires access to the configured devices.
- Compares the actual states against the desired state.
- Generates CSV and Markdown reports of the results.

## Breaking changes

- Loose mode to ignore playbook errors is no longer supported in ANTA mode.
- ANTA mode exclusively supports the newer "list-of-dicts" data models in the structured configuration file input. For further details, consult the AVD 4.x.x [porting guides](https://avd.sh/en/stable/docs/porting-guides/4.x.x.html#data-model-changes-from-dict-of-dicts-to-list-of-dicts).
- Inputs for hardware tests have been updated. See [Input variables](#input-variables) below.
- Changes to CSV and Markdown reports:
  - Hardware tests are now collapsed.
  - Sorting of test results is now done per device as opposed to per category.
  - Test categories, descriptions and inputs have been improved to follow ANTA.
  - CSV report headers updated from `test_id,node,test_category,test_description,test,result,failure_reason` to `id,dut,categories,test,description,inputs,result,messages`

## Roadmap

!!! note
    Subject to change. No commitments implied.

- Add more ANTA tests generated from the structured configuration

!!! tip
    You can provide your own custom ANTA catalogs using any of the available [ANTA tests](https://anta.arista.com/stable/api/tests/) to the AVD `eos_validate_state` role. Please refer to the [Custom ANTA catalog](#custom-anta-catalog) section for more details.

## Expected changes

- You should expect faster execution, and if not please report on the GitHub [discussions board](https://github.com/aristanetworks/avd/discussions)
- Tests skipped by ANTA will be marked as `SKIPPED` in the final reports.
- All tests will be removed from the catalog for a device flagged as undeployed using the host level variable [`is_deployed: false`](https://avd.sh/en/stable/roles/eos_designs/docs/input-variables.html#flagging-a-device-as-not-deployed). Additionally, all tests take into account the `is_deployed` variable value and remove tests accordingly.

!!! warning
    Tests can also be automatically removed from the catalogs depending on the structured configuration of the devices. ANTA is therefore not aware of these tests and they will not appear in the final report. For example, the `AvdTestMLAG` tests will not be present in the test catalog of a device that does not have an MLAG configuration in its structured configuration.

- BGP tests will only run if `service_routing_protocols_model` is set to `multi-agent` in the structured configuration file.

!!! note
    Starting from version 4.30.1F, `service_routing_protocols_model` is preset to `multi-agent` by default on EOS devices.

- Inband management reachability test has been refactored to support the new AVD 4.x.x inband management [data model](https://avd.sh/en/stable/roles/eos_designs/docs/input-variables.html#node-type-inband-management).

## How to run eos_validate_state in ANTA mode

- The "anta" Python package is now part of the `requirements.txt` file. Please refer to the [AVD Additional Python Libraries required](https://avd.sh/en/stable/docs/installation/collection-installation.html#required-python-libraries) section to proceed.

- Run eos_validate_state playbook by setting the variable `use_anta=true`.

  This can be set for instance in your group_vars or under the task in your playbook.

  If you `use_anta=false` which is the default, the current version of `eos_validate_state` leveraging Ansible asserts will be run.

- Ansible tags are supported for backwards compatibility until AVD version 5.0.0.
  To run/skip tests use `--tags` or `--skip-tags`.

  ```shell
  ansible-playbook playbooks/fabric-validate.yaml --tags routing_table
  ```

- You can now run the eos_validate_state role in check_mode. This will produce a report of tests that will be performed without running the tests on your network. Tests will be marked as `NOT RUN` in the final reports.

  ```shell
  ansible-playbook playbooks/fabric-validate.yaml --check
  ```

- You can increase the Ansible verbosity by adding multiple `-v` when running the playbook. This will give you visibility on which [test categories](#test-categories) are being removed from a device's catalog by AVD according to the structured configurations.

  ```shell
  ansible-playbook playbooks/fabric-validate.yaml -v
  ```

!!! info
    ANTA mode also supports other functionalities. For more details, please refer to the [input variables](#input-variables) below.

## Test categories

!!! note
    New tests are marked with the (New) string.

- AvdTestHardware (Ansible tags: `hardware`, `platform_information`)
  - VerifyEnvironmentPower: Validate environment power supplies status.
  - VerifyEnvironmentCooling: Validate environment fan status.
  - VerifyTemperature: Validate environment temperature.
  - VerifyTransceiversManufacturers: Validate transceivers manufacturer.

- AvdTestNTP (Ansible tags: `ntp`)
  - VerifyNTP: Validate NTP status.

- AvdTestInterfacesState (Ansible tags: `interfaces_state`)
  - VerifyInterfacesStatus: Validate interfaces status.
    - Ethernet interfaces
    - Port-channel interfaces
    - Vlan interfaces
    - Loopback interfaces
    - Vxlan1 interface
    - DPS interfaces

- AvdTestP2PIPReachability (Ansible tags: `ip_reachability`)
  - VerifyReachability: Validate IP reachability for point-to-point l3 ethernet interfaces.

- AvdTestInbandReachability (Ansible tags: `loopback_reachability`, `loopback0_reachability`, `optional`)
  - VerifyReachability: Validate loopback reachability from the inband management VLAN interface.

- AvdTestLoopback0Reachability (Ansible tags: `loopback_reachability`, `loopback0_reachability`)
  - VerifyReachability: Validate loopback reachability between devices.

- AvdTestLLDPTopology (Ansible tags: `lldp_topology`)
  - VerifyLLDPNeighbors: Validate LLDP topology.

- AvdTestMLAG (Ansible tags: `mlag`)
  - VerifyMlagStatus: Validate MLAG status.

- AvdTestRoutingTable (Ansible tags: `routing_table`)
  - VerifyRoutingTableEntry: Validate remote Loopback0 address and source interface for Vxlan1 interface are in the routing table.

- AvdTestBGP (Ansible tags: `bgp_check`)
  - VerifyBGPSpecificPeers: Validate IP BGP and BGP EVPN sessions state.
  - VerifyRoutingProtocolModel: Validate ArBGP is configured and operating.

- AvdTestReloadCause (Ansible tags: `reload_cause`, `optional`, `never`)
  - VerifyReloadCause: Validate last reload cause. (Optional)

- (New) AvdTestAPIHttpsSSL (No Ansible tags, use the new `skip_tests` variable instead)
  - VerifyAPIHttpsSSL: Validate eAPI HTTPS SSL profile status.

- (New) AvdTestIPSecurity (No Ansible tags, use the new `skip_tests` variable instead)
  - VerifySpecificIPSecConn: Validates the establishment of IP security connections for a peer within the default VRF. In its current state, the test validates only IPsec connections defined as static peers under the `router path-selection` section of the configuration.

- (New) AvdTestStun (No Ansible tags, use the new `skip_tests` variable instead)
  - VerifyStunClient: Validates the presence of a STUN client translation for a given source IPv4 address and port for WAN scenarios. The list of expected translations for each device is built by searching local interfaces in each path-group.

## Input variables

```yaml
# Root directory.
root_dir: <str; | default="{{ inventory_dir }}">

# Output directory.
output_dir_name: <str; | default="intended">
output_dir: <str; | default="{{ root_dir }}/{{ output_dir_name }}">

# Output for test catalog YAML files if save_catalog is set to true.
test_catalogs_dir_name: "<str; | default="test_catalogs">
test_catalogs_dir: <str; | default="{{ output_dir }}/{{ test_catalogs_dir_name }}">

# Output directory for eos_validate_state reports.
eos_validate_state_name: <str; | default="reports">
eos_validate_state_dir: <str; | default="{{ root_dir }}/{{ eos_validate_state_name }}">

# Output for test results JSON files if save_results is set to true.
test_results_dir_name: <str; | default="test_results">
test_results_dir: <str; | default="{{ eos_validate_state_dir }}/{{ test_results_dir_name }}">

# Reports name.
eos_validate_state_md_report_path: <str; | default="{{ eos_validate_state_dir }}/{{ fabric_name }}-state.md">
eos_validate_state_csv_report_path: <str; | default="{{ eos_validate_state_dir }}/{{ fabric_name }}-state.csv">

# Input directory for structured configuration files.
structured_dir_name: <str; | default="structured_configs">
structured_dir: <str; | default="{{ output_dir }}/{{ structured_dir_name }}">

# Structured configuration files format.
avd_structured_config_file_format: "yml"

# Input directory for custom ANTA catalogs.
custom_anta_catalogs_dir_name: <str; | default="custom_anta_catalogs">
custom_anta_catalogs_dir: <str; | default="{{ root_dir }}/{{ custom_anta_catalogs_dir_name }}">

# Allow different manufacturers.
accepted_xcvr_manufacturers: <list; | default="['Arastra, Inc.', 'Arista Networks']">

# Allow different states for power supplies.
accepted_pwr_supply_states: <list; default=['ok']>

# Allow different states for fans.
accepted_fan_states: <list; default=['ok']">

# Generate CSV results file.
validation_report_csv: <bool; default=True>

# Generate MD results file.
validation_report_md: <bool; default=True>

# Print only FAILED tests.
only_failed_tests: <bool; default=False>

# Variable to enable ANTA eos_validate_state.
use_anta: <bool; default=False>

# Save each device test catalog to 'test_catalogs_dir'.
save_catalog: <bool; default=False>

# Logging level for the ANTA libraries.
logging_level: <str; "INFO" | "WARNING" | "ERROR" | "CRITICAL" | "DEBUG"; default="WARNING">

# The variable `skip_tests` can be used for running/skipping test categories.
# Examples
# skip_tests:
#   - category: AvdTestHardware
#
# or to skip specific tests (ANTA test names) in a given category for more granularity:
# skip_tests:
#  - category: AvdTestHardware
#    tests:
#      - VerifyEnvironmentCooling
#      - VerifyTemperature
#  - category: AvdTestBGP
#    tests:
#      - VerifyBGPSpecificPeers
skip_tests:
  - category: <str>
    # Optional tests
    tests:
      - <str>
```

## Custom ANTA catalog

You can provide custom ANTA catalogs to the AVD `eos_validate_state` role. By default, AVD will search for catalog YAML files in the `custom_anta_catalogs` directory and incorporate these tests into the existing dynamically created catalog from AVD. The custom catalog files must be named as follows:

- `<hostname>.yml` or `<hostname>.yaml`
- `<group>.yml` or `<group>.yaml`

When specifying a group, it must be a group from the Ansible inventory. The custom tests will then be added to all devices that are part of this group. You can also use the `all` group to target all the devices in your inventory. The directory where the custom catalogs are stored can be changed with the `custom_anta_catalogs_dir` variable.

!!! warning
    The `skip_tests` variable will ONLY skip the dynamically generated tests from the AVD validate state role. It will **not** skip tests added from custom catalogs.

!!! info
    The final catalog will be validated by ANTA before running the tests on your network. Duplicate tests with the same inputs will be automatically removed. Therefore, dynamically generated tests by AVD will never be overwritten. To overwrite them, you should first skip them using the `skip_tests` variable and provide your own tests with inputs via a custom catalog.

## Example playbook

```yaml
---
- name: validate states on EOS devices using ANTA
  hosts: DC1
  gather_facts: false
  tasks:
    - name: validate states on EOS devices
      ansible.builtin.import_role:
        name: arista.avd.eos_validate_state
      vars:
        # To enable ANTA
        use_anta: true
        # To save catalogs
        save_catalog: true
```

## Known issues

- `[__NSCFConstantString initialize] may have been in progress in another thread when fork() was called.` This issue affects OSX users only and is covered in Ansible documentation: https://docs.ansible.com/ansible/latest/reference_appendices/faq.html#running-on-macos-as-a-control-node.
