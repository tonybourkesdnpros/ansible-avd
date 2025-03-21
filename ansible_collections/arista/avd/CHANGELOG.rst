========================
Arista.Avd Release Notes
========================

.. contents:: Topics

v4.9.0
======

Release Summary
---------------

Release 4.9.0 - See documentation on avd.arista.com for details.

Minor Changes
-------------

- Bump(pyavd): Add support for Python 3.9 in PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4051
- Doc(eos_cli_config_gen): Include docs for router segment-security by @jonxstill in https://github.com/aristanetworks/avd/pull/4059
- Doc: Add notes about using cv_deploy for CV Pathfinder by @gmuloc in https://github.com/aristanetworks/avd/pull/4044
- Doc: Added the table of WAN validation by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/4125
- Doc: Contribution Guide Updates by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3766
- Doc: Fix mkdocs broken requirement links in roles by @gmuloc in https://github.com/aristanetworks/avd/pull/4039
- Doc: Minor grammar edits. by @blitzeditor in https://github.com/aristanetworks/avd/pull/3362
- Doc: Minor updates to Development Tooling guide. by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4067
- Doc: Semantic Versioning by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3417
- Doc: Update installation guide with PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4076
- Doc: add CVaaS regional URLs to cv_deploy by @noredistribution in https://github.com/aristanetworks/avd/pull/4092
- Feat(containers): switch to pyavd and editable install for container build by @ankudinov in https://github.com/aristanetworks/avd/pull/4087
- Feat(eos_cli_config_gen): Add Patch-Panel Connector commands by @ccsnw in https://github.com/aristanetworks/avd/pull/4063
- Feat(eos_cli_config_gen): Add option for `ospf_type` when redistributing OSPF into BGP by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4029
- Feat(eos_cli_config_gen): Add support for 'no bgp redistribute-internal' by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/4033
- Feat(eos_cli_config_gen): Add support for MACsec fallback to unprotected traffic by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4028
- Feat(eos_cli_config_gen): Add support for Postcard telemetry by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3642
- Feat(eos_cli_config_gen): Add support for Router BGP missing-policy for address-family all by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/4034
- Feat(eos_cli_config_gen): Add support for dot1x captive portal and supplicant commands by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4023
- Feat(eos_cli_config_gen): Add support for permit response traffic nat under ip acls by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4128
- Feat(eos_cli_config_gen): Adding option for arp cache persistent and arp persistent refresh-delay by @bjmeuer in https://github.com/aristanetworks/avd/pull/4109
- Feat(eos_cli_config_gen): Support of BGP default-originate per VRF #3941 by @mmaaloul in https://github.com/aristanetworks/avd/pull/4122
- Feat(eos_cli_config_gen): Support of static IPv6 neighbor entries by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/4075
- Feat(eos_designs): Add platform settings for WAN devices by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/4027
- Feat(eos_designs): Add support for 'uplink_mtu' under node config by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/4040
- Feat(eos_designs): Add support for directly connected WAN HA by @gmuloc in https://github.com/aristanetworks/avd/pull/3720
- Feat(eos_designs): Add support to enable BGP peering with wan provider by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/4079
- Feat(eos_designs): Allow 'evpn_vlan_bundle' to be set up at tenant level by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/4093
- Feat(eos_designs): Allow reuse of cross-device BGP peer ip by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/4050
- Feat(eos_designs): Disable per interface MTU for 7010TX by @xaviramon in https://github.com/aristanetworks/avd/pull/4053
- Feat(eos_designs): Enforce unicity of region IDs and per-region site IDs for CV Pathfinder by @gmuloc in https://github.com/aristanetworks/avd/pull/4121
- Feat(eos_validate_state): Add support for ANTA v1.0.0 by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/4123
- Feat(eos_validate_state): Added the validation for IP security connections by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/3911
- Feat(eos_validate_state): Added the validation for STUN client configurations by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/3898
- Refactor(cv_deploy): Optimize creation of configlet containers by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3950
- Refactor(eos_cli_config_gen): Addressed missed comments for patch-panel by @gmuloc in https://github.com/aristanetworks/avd/pull/4078
- Refactor(eos_cli_config_gen): Move eos_cli_config_gen to pyavd by @gmuloc in https://github.com/aristanetworks/avd/pull/4117
- Refactor(eos_designs): Move eos_designs Python modules to PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4120
- Refactor(eos_designs): Move eos_designs_facts to PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4110
- Refactor(eos_designs): Move eos_designs_shared_utils to PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4126
- Refactor(plugins): Deprecate various unused Ansible plugins by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4166
- Refactor(plugins): Move internal AVD code to PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4140
- Refactor(plugins): Move internal cv_client code to PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4141
- Refactor(plugins): Move jinja filter code for `arista.avd.default` to PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4047
- Refactor(plugins): Move jinja filter code for arista.avd.add_md_toc to PyAVD by @gmuloc in https://github.com/aristanetworks/avd/pull/4104
- Refactor(plugins): Move jinja filter code for arista.avd.convert_dicts to PyAVD by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4069
- Refactor(plugins): Move jinja filter code for arista.avd.encrypt and arista.avd.decrypt to PyAVD by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/4135
- Refactor(plugins): Move jinja filter code for arista.avd.generate_esi to PyAVD by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4114
- Refactor(plugins): Move jinja filter code for arista.avd.generate_lacp_id to PyAVD by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4139
- Refactor(plugins): Move jinja filter code for arista.avd.generate_route_target to PyAVD by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4101
- Refactor(plugins): Move jinja filter code for arista.avd.hide_passwords to PyAVD by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4112
- Refactor(plugins): Move jinja filter code for arista.avd.is_in_filter to PyAVD by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4133
- Refactor(plugins): Move jinja filter code for arista.avd.list_compress to PyAVD by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4099
- Refactor(plugins): Move jinja filter code for arista.avd.natural_sort to PyAVD by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4068
- Refactor(plugins): Move jinja filter code for arista.avd.range_expand to PyAVD by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/4138
- Refactor(plugins): Move jinja filter code for arista.avd.snmp_hash to PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4136
- Refactor(plugins): Move jinja filter code for arista.avd.status_render to PyAVD by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4142
- Refactor(plugins): Move jinja test code for arista.avd.contains to PyAVD by @gmuloc in https://github.com/aristanetworks/avd/pull/4131
- Refactor(plugins): Move jinja test code for arista.avd.defined to PyAVD by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4143
- Refactor(plugins): Move schema code and schema fragments to PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4130
- Refactor: Deprecate Python3.9 support by @gmuloc in https://github.com/aristanetworks/avd/pull/4177
- Refactor: Move requirements to PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4147

Bugfixes
--------

- Fix(containers): Add "remoteUser": "avd" to devcontainer by @carlbuchmann in https://github.com/aristanetworks/avd/pull/4043
- Fix(cv_deploy): Improve SWG API handling for Zscaler internet exit by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4090
- Fix(eos_cli_config_gen): BGP models has supress-map which is not present in EOS commands. by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/4054
- Fix(eos_cli_config_gen): Fix MSDP template typo for sa_filter.out_list by @gusmb in https://github.com/aristanetworks/avd/pull/4161
- Fix(eos_cli_config_gen): Fix the templates for event-handlers by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4055
- Fix(eos_designs)!: Remove eBGP LAN outbound route-map for WAN by @gmuloc in https://github.com/aristanetworks/avd/pull/4107
- Fix(eos_designs): Address ipv4_acl_in/out not working for WAN l3 subinterfaces by @gmuloc in https://github.com/aristanetworks/avd/pull/4116
- Fix(eos_designs): Inband mgmt route-map and prefix-list should not be applied without overlay_routing_protocol by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4045
- Fix(eos_designs): WAN Exclude interface IP address from direct internet-exit NAT ACL by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/4096
- Fix(eos_designs): core_interfaces generates invalid config if ASN is not defined for the p2p_links/p2p_links_profiles by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4046
- Fix(eos_validate_state): Update error message when a device does not have httpapi _sub_plugin by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/4049
- Fix: Adjust inventory group names in molecule tests to follow Ansible guidelines by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/4097
- Fix: Change the required arguments for eos_cli_config_gen action plugin by @gmuloc in https://github.com/aristanetworks/avd/pull/4152

New Modules
-----------

- arista.avd.eos_cli_config_gen - Generate AVD EOS device configurations and documentations

v4.8.0
======

Release Summary
---------------

Release 4.8.0 - See documentation on avd.arista.com for details.

Minor Changes
-------------

- Bump(eos_validate_state): ANTA Update eos_validate_state code to support ANTA v0.14.0 by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3871
- Bump(requirements): Bump black from 24.3.0 to 24.4.0 in /ansible_collections/arista/avd by @dependabot in https://github.com/aristanetworks/avd/pull/3860
- Bump(requirements): Bump black from 24.4.0 to 24.4.1 in /ansible_collections/arista/avd by @dependabot in https://github.com/aristanetworks/avd/pull/3906
- Bump(requirements): Bump black from 24.4.1 to 24.4.2 in /ansible_collections/arista/avd by @dependabot in https://github.com/aristanetworks/avd/pull/3913
- Bump(requirements): Set minimum ansible-core version to 2.15.x and maximum to 2.17.x by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3927
- Bump(requirements): Support newer jsonschema versions by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3934
- Doc(eos_cli_config_gen): Add missing switchport port security table to documentation by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3880
- Doc(eos_designs): Fix indentation in WAN how-to by @gmuloc in https://github.com/aristanetworks/avd/pull/4010
- Doc(eos_validate_state): Add link for OSX fork issue by @gmuloc in https://github.com/aristanetworks/avd/pull/3902
- Doc(plugins): Fix wrong module name in eos_designs_structured_config module doc by @gmuloc in https://github.com/aristanetworks/avd/pull/3795
- Doc: Fix examples for connected endpoints using deprecated data-model in input-varaibles.md by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3989
- Doc: Move documentation of mlag_ibgp_peering_vrfs to network services section. by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3992
- Doc: Readme updates to align with the new Red Hat template by @JulioPDX in https://github.com/aristanetworks/avd/pull/4024
- Doc: Release 4.7.1 by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3846
- Doc: Update CSS to bring `code` to 100% size by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3917
- Doc: Update installation guide to avoid 'pipx' by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3863
- Doc: Updated the documentation for IPv4 ACL by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/3955
- Feat(eos_cli_config_gen):  Add policy-maps qos police. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3620
- Feat(eos_cli_config_gen): Add DHCP server options for TFTP and DNS by @jrecchia1029 in https://github.com/aristanetworks/avd/pull/3993
- Feat(eos_cli_config_gen): Add FQDN & UFQDN support for ike profile local-id by @gmuloc in https://github.com/aristanetworks/avd/pull/3832
- Feat(eos_cli_config_gen): Add IPsec and NAT options to tunnel_interfaces. by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3830
- Feat(eos_cli_config_gen): Add InfluxDB support by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3705
- Feat(eos_cli_config_gen): Add Regex pattern for region/zone/site name for router_adapative_virtual_topology by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/4026
- Feat(eos_cli_config_gen): Add aaa unresponsive action under global dot1x by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3739
- Feat(eos_cli_config_gen): Add capability to disable address-only for connectivity monitors by @gmuloc in https://github.com/aristanetworks/avd/pull/3867
- Feat(eos_cli_config_gen): Add eos_cli support under router_isis. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3745
- Feat(eos_cli_config_gen): Add event-handler trigger on-maintenance. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3629
- Feat(eos_cli_config_gen): Add l4 to application traffic recognition by @colinmacgiolla in https://github.com/aristanetworks/avd/pull/3780
- Feat(eos_cli_config_gen): Add option for dot1x aaa accounting update interval x seconds. by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4017
- Feat(eos_cli_config_gen): Add router internet-exit. by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3748
- Feat(eos_cli_config_gen): Add router segment security by @colinmacgiolla in https://github.com/aristanetworks/avd/pull/3782
- Feat(eos_cli_config_gen): Add router service-insertion subcommands for Internet Exit by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3757
- Feat(eos_cli_config_gen): Add support for BGP TCP AO. by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3853
- Feat(eos_cli_config_gen): Add support for L2 in-place adjacency replacement (IAR) by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/3990
- Feat(eos_cli_config_gen): Add support for copp policy-maps. by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3895
- Feat(eos_cli_config_gen): Add support for isis spf-interval hold timer. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3912
- Feat(eos_cli_config_gen): Add support for raw `eos_cli` under  `router_bgp` by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3673
- Feat(eos_cli_config_gen): Add transceiver.frequency under ethernet_interfaces by @ccsnw in https://github.com/aristanetworks/avd/pull/4003
- Feat(eos_cli_config_gen): Adding 'ip igmp host-proxy' interface support by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3657
- Feat(eos_cli_config_gen): Adding segment-security in hardware counters. by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4000
- Feat(eos_cli_config_gen): Enhance event-handlers model to accommodate other triggers with their specificities. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3878
- Feat(eos_cli_config_gen): Implement managing RCF. by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3798
- Feat(eos_cli_config_gen): Option to set RCF address-family ipv4, ipv6 and evpn by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3814
- Feat(eos_cli_config_gen): Option to set RCF for route bgp ipv4/ipv6 mulit-cast and VRF by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3821
- Feat(eos_cli_config_gen): Option to set RCF route bgp address-family vpn-ipv6/ipv4 and redistribute. by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3819
- Feat(eos_cli_config_gen): Support SA lifetime for IP sec by @gmuloc in https://github.com/aristanetworks/avd/pull/3875
- Feat(eos_cli_config_gen): Support activity polling-interval for router multicast. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3893
- Feat(eos_cli_config_gen): Support additional options for IP DHCP relay and IPv6 DHCP relay by @bjmeuer in https://github.com/aristanetworks/avd/pull/3925
- Feat(eos_cli_config_gen): Support additional options for IPv6 ND under SVIs by @bjmeuer in https://github.com/aristanetworks/avd/pull/3935
- Feat(eos_cli_config_gen): Support for MSS Clamping on ethernet interfaces. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4018
- Feat(eos_cli_config_gen): Support for additional commands under the EVPN address family by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/3881
- Feat(eos_cli_config_gen): Support for configuring logging level facilities by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/3944
- Feat(eos_cli_config_gen): Support logging transceiver in monitor layer1 by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3991
- Feat(eos_cli_config_gen): Support port-only option in IP NAT pools by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3840
- Feat(eos_cli_config_gen): add hardware flow tracking standard record format support by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3681
- Feat(eos_designs): Add knob for IS-IS system-id format by @ZoeyFahner-Arista in https://github.com/aristanetworks/avd/pull/3677
- Feat(eos_designs): Add metadata for Zscaler internet-exit by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3886
- Feat(eos_designs): Add more granular settings for flow_tracking by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3776
- Feat(eos_designs): Add optional cv-pathfinder site for pathfinders by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3904
- Feat(eos_designs): Add pim ipv4 sparse_mode on core_interfaces/l3_edge interfaces. by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3831
- Feat(eos_designs): Add platform specific management security entropy source settings. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3810
- Feat(eos_designs): Add sample rate to sflow settings in eos_designs. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3891
- Feat(eos_designs): Add structured_config support in platform_settings. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3807
- Feat(eos_designs): Add support for Zscaler internet-exit policy by @gmuloc in https://github.com/aristanetworks/avd/pull/3833
- Feat(eos_designs): Add support for ipv4_acl_in/out on SVIs defined under network services. by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3791
- Feat(eos_designs): Add support for local internet exit by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3952
- Feat(eos_designs): Add support for mlag_peer_ipv6_pool by @Xatrekak in https://github.com/aristanetworks/avd/pull/3885
- Feat(eos_designs): Add support for setting mgmt_gateway under the node settings. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3799
- Feat(eos_designs): Added for L3LS P2P addressing via Spine using "downlink_pools" data model by @hubert-arista in https://github.com/aristanetworks/avd/pull/3693
- Feat(eos_designs): Allow VLAN Aware Bundles even if common evpn_vlan_aware_bundles is false by @bjmeuer in https://github.com/aristanetworks/avd/pull/3827
- Feat(eos_designs): Extend the functionality of the is_deployed flag to shutdown BGP peerings. by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3916
- Feat(eos_designs): IPv4/IPv6 address-family configuration for bgp_peer_groups defined under network services. by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3887
- Feat(eos_designs, eos_cli_config_gen): Add BFD option for underlay ISIS by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3683
- Feat(eos_designs,eos_cli_config_gen): Add support for MLAG port-channels to endpoints with PTP by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3672
- Feat(eos_validate_state): Added the validation for BGP address families(link-state, path-selection and ipv4/ipv6 sr-te) by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/3872
- Feat(plugins): Revert support braces in range_expand filter (#3244)" by @carlbuchmann in https://github.com/aristanetworks/avd/pull/4013
- Feat(plugins): Support braces in range_expand filter by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3244
- Feat(pyavd): Add optional dependency pyavd by @dlobato in https://github.com/aristanetworks/avd/pull/3852
- Fix(pyavd): Remove accidental requirement for PyYAML by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3838
- Refactor(eos_cli_config_gen): Modifying the data-model for management security entropy source by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3841
- Refactor(eos_designs): Minor code adjustments caught by latest pylint by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4021
- Refactor(eos_designs): Source more Zscaler metadata from lookup plugin by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3977
- Refactor(plugins): Move WAN internet-exit zscaler integration to eos_designs by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4002
- Refactor(plugins): Rewrite add_md_toc by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/4011
- Refactor(plugins): Update cloudvision api with latest proto files by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3995
- Refactor(plugins): Update cv_client to use SetSome for topology studio inputs by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3803
- Refactor(pyavd): Lazy imports of vendored code by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3923
- Revert: "Bump pre-commit-ci/lite-action from 1.0.0 to 1.0.2" by @gmuloc in https://github.com/aristanetworks/avd/pull/3868

Bugfixes
--------

- Fix(cv_deploy): Detect pathfinder metadata studio version and skip unsupported fields by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3986
- Fix(cv_deploy): Fix internet exit metadata by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3956
- Fix(dhcp_provisioner): Support custom `node_type_keys` as a list of dicts. by @philippebureau in https://github.com/aristanetworks/avd/pull/3813
- Fix(eos_cli_config_gen): Fix the schema and template for action in event-handler. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/4007
- Fix(eos_cli_config_gen): Missing variable protection in Jinja Templates. by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/4005
- Fix(eos_cli_config_gen): Remove requirement for original_ip to be unique under interface IP NAT by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3900
- Fix(eos_cli_config_gen): Render access vlan on port-channel interfaces if mode is dot1q-tunnel. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3920
- Fix(eos_designs): Connected endpoints ESI should only be configured on EVPN VTEPs. by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/4020
- Fix(eos_designs): Fix code error for monitor_sessions for network_ports by @gmuloc in https://github.com/aristanetworks/avd/pull/3818
- Fix(eos_designs): Fix missing features from LACP fallback individual by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3862
- Fix(eos_designs): Inband ztp works with inband_mgmt_ip key by @jrecchia1029 in https://github.com/aristanetworks/avd/pull/3908
- Fix(eos_designs): Make WAN RRs route-reflector clients of each other by @gmuloc in https://github.com/aristanetworks/avd/pull/3921
- Fix(eos_designs): Remove the remaining trailing slashes in schema by @gmuloc in https://github.com/aristanetworks/avd/pull/3961
- Fix(eos_designs): Sanitize interface name in STUN profile name by @gmuloc in https://github.com/aristanetworks/avd/pull/3949
- Fix(eos_designs): WAN Internet-exit fixes for Zscaler integration by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3984
- Fix(eos_designs): Wrong IPsec profile name for Zscaler by @gmuloc in https://github.com/aristanetworks/avd/pull/3948
- Fix(eos_validate_state): ANTA Remove the use of the eos_design's "type" variable by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3870
- Fix(plugins): Fix cv_zscaler_endpoints lookup plugin by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3946
- Fix(plugins): Handle md-toc v9 by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3837
- Fix: Fixing event-handlers in eos_designs_unit_tests molecule scenario. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3938
- Fix: Remove "not RFC1918 IPs" from examples. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3800

v4.7.1
======

Release Summary
---------------

Release 4.7.1 - See documentation on avd.arista.com for details.

Bugfixes
--------

- Fix(dhcp_provisioner): Support custom `node_type_keys` as a list of dicts. (#3813) by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3842
- Fix(plugins): Handle md-toc v9 (#3837) by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3845
- Fix(pyavd): Remove accidental requirement for PyYAML (#3838) by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3844

v4.7.0
======

Release Summary
---------------

Release 4.7.0 - See documentation on avd.arista.com for details.

Minor Changes
-------------

- Bump(eos_validate_state): ANTA Bump and update code for ANTA v0.13.0 by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3726
- Bump: Update black by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3760
- Doc(cv_deploy): Add supported CloudVision versions by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3788
- Doc(eos_cli_config_gen): Add Dps1 to flow tracking output in device config by @gmuloc in https://github.com/aristanetworks/avd/pull/3786
- Doc(eos_cli_config_gen, eos_designs): Add missing schema files by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3704
- Doc: Adding eos designs diagrams for mpls and l2ls by @JulioPDX in https://github.com/aristanetworks/avd/pull/3790
- Doc: Clean documentation for WAN by @gmuloc in https://github.com/aristanetworks/avd/pull/3665
- Doc: Fix CV playbook example in intro to ansible and avd by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3778
- Doc: Fix YAML in schema docs for multiline descriptions with blank lines by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3651
- Doc: Updating diagrams for MPLS example by @JulioPDX in https://github.com/aristanetworks/avd/pull/3784
- Doc: Updating intro to avd and ansible diagrams by @JulioPDX in https://github.com/aristanetworks/avd/pull/3783
- Feat(deploy_to_cv): Add support for waiting for Change Control to be completed before returning by @sugetha24 in https://github.com/aristanetworks/avd/pull/3732
- Feat(eos_cli_config_gen): Add 1-step Boundary Clock support by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3666
- Feat(eos_cli_config_gen): Add FIPS and hostkey.client features to management_ssh by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3571
- Feat(eos_cli_config_gen): Add custom comments at the top of the rendered configuration. by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3738
- Feat(eos_cli_config_gen): Add more 'pim ipv4' interface commands by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3663
- Feat(eos_cli_config_gen): Add neighbors key to router_bgp.address_family_evpn. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3641
- Feat(eos_cli_config_gen): Add support for Interface Vxlan, vxlan bridging vtep-to-vtep by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3718
- Feat(eos_cli_config_gen): Add support for setting the ASN notation by @colinmacgiolla in https://github.com/aristanetworks/avd/pull/3678
- Feat(eos_cli_config_gen): Add support for switchport port-security. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3561
- Feat(eos_cli_config_gen): Extend match lists to support IPv4 and IPv6 by @colinmacgiolla in https://github.com/aristanetworks/avd/pull/3770
- Feat(eos_cli_config_gen): Support for EVPN Multihoming IP Mass-withdrawal by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3656
- Feat(eos_cli_config_gen): add sFlow sample output subinterface support by @philippebureau in https://github.com/aristanetworks/avd/pull/3458
- Feat(eos_designs):  Replace wan_role checks with helper cached_property utils by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3639
- Feat(eos_designs): Add 'dhcp_ip_address' under 'l3_interfaces' node settings by @gmuloc in https://github.com/aristanetworks/avd/pull/3686
- Feat(eos_designs): Add 'maximum_routes_warning_only' to the 'bgp_peers' in network_services data model by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3645
- Feat(eos_designs): Add 1-step Boundary Clock support by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3668
- Feat(eos_designs): Add Vxlan1 VRF VNI for WAN VRFs on Pathfinders by @gmuloc in https://github.com/aristanetworks/avd/pull/3746
- Feat(eos_designs): Add ability to override wan control plane policy by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3690
- Feat(eos_designs): Add default_preference and excluded for wan_path_groups by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3648
- Feat(eos_designs): Add eBGP LAN HA support for CV Pathfinder by @gmuloc in https://github.com/aristanetworks/avd/pull/3494
- Feat(eos_designs): Add filter.allow_vrfs and filter.deny_vrfs by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3653
- Feat(eos_designs): Add flowtracking on WAN Router LAN uplinks by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3679
- Feat(eos_designs): Add sflow_settings by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3078
- Feat(eos_designs): Add support for hop count lowest in load-balancing policies by @gmuloc in https://github.com/aristanetworks/avd/pull/3646
- Feat(eos_designs): Add support for ipv4_acls with field replacement by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3750
- Feat(eos_designs): Add system mac address to structured config under 'metadata'. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3658
- Feat(eos_designs): Add wan_carrier and circuit_id to l3 interface description by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3649
- Feat(eos_designs): Add wan_vni for WAN VRF by @gmuloc in https://github.com/aristanetworks/avd/pull/3600
- Feat(eos_designs): Allow custom name for LAN_HA path-group by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3723
- Feat(eos_designs): Allow custom name for pathfinder Flow tracker tracker and exporter settings by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3721
- Feat(eos_designs): Allow overlapping VLAN IDs under network services by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3722
- Feat(eos_designs): Allow to control DPS timers at the wan_path_group level by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3625
- Feat(eos_designs): Allow to disable IPsec on dynamic peers for a path-group avd by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3695
- Feat(eos_designs): Configure BFD timers higher than DPS timeouts for WAN BGP neighbors by @amitsagar-arsita in https://github.com/aristanetworks/avd/pull/3586
- Feat(eos_designs): Dot1x unauthorized access|native vlan membership egress to ethernet interfaces via port_profile by @laxmikantchintakindi in https://github.com/aristanetworks/avd/pull/3779
- Feat(eos_designs): Enable KERNELFIB_PROGRAM_ALL_ECMP for all wan routers by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3689
- Feat(eos_designs): GTSM configuration to limit the TTL permitted for bgp peering to 1 for WAN by @amitsagar-arsita in https://github.com/aristanetworks/avd/pull/3607
- Feat(eos_designs): IPv6 inband management settings by @emilarista in https://github.com/aristanetworks/avd/pull/3382
- Feat(eos_designs): Implement WAN/LAN redistribution for eBGP LAN by @gmuloc in https://github.com/aristanetworks/avd/pull/3602
- Feat(eos_designs): L2 inband ztp functionality by @jrecchia1029 in https://github.com/aristanetworks/avd/pull/3660
- Feat(eos_designs): Make DPS1 interface MTU 9k by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3619
- Feat(eos_designs): Option to define evpn_vlan_bundle for SVIs by @bjmeuer in https://github.com/aristanetworks/avd/pull/3623
- Feat(eos_designs): STUN SSL profile support by @amitsagar-arsita in https://github.com/aristanetworks/avd/pull/3636
- Feat(eos_designs): Update platform.py with 7358X4 by @colinmacgiolla in https://github.com/aristanetworks/avd/pull/3667
- Feat(eos_designs): Uplink type 'lan' for WAN routers by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3593
- Feat(eos_designs): public_ip input field support for devices behind NAT by @amitsagar-arsita in https://github.com/aristanetworks/avd/pull/3652
- Feat(eos_validate_state): ANTA Provide custom ANTA catalog files to validate state by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3655
- Feat(eos_validate_state): Added support to validate DPS interface state by @MaheshGSLAB in https://github.com/aristanetworks/avd/pull/3692
- Feat(plugins): Add "unique_keys" in avdschema. by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3725
- Feat(plugins): Add ISIS support to encrypt and decrypt filters by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3662
- Fix(deploy_to_cv): Do not add Pathfinders to Routers section of metadata studio by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3680
- Refactor(deploy_to_cv): Dynamic timeouts and library support for username/password by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3762
- Refactor(deploy_to_cv): Ignore missing metadata by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3703
- Refactor(deploy_to_cv): Remove metadata studio version detection by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3781
- Refactor(deploy_to_cv): Set default values for constraints in metadata studio by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3773
- Refactor(deploy_to_cv): Update "role" field for "transit region" in metadata studio by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3744
- Refactor(eos_designs): Better security for IPsec configuration for WAN by @gmuloc in https://github.com/aristanetworks/avd/pull/3543
- Refactor(eos_designs): CV Pathfinder metadata updates by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3697
- Refactor(eos_designs): Force WAN HA to be either enabled or disabled by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3772
- Refactor(eos_designs): Grouping name generation of  WAN profiles and policies by @gmuloc in https://github.com/aristanetworks/avd/pull/3638
- Refactor(eos_designs): Make DHCP default route generated by default by @gmuloc in https://github.com/aristanetworks/avd/pull/3724
- Refactor(eos_designs): Make Flow tracking enabled on Dps1 interface only by @gmuloc in https://github.com/aristanetworks/avd/pull/3767
- Refactor(eos_designs): Make id mandatory for AVTs when mode is cv-pathfinder by @gmuloc in https://github.com/aristanetworks/avd/pull/3707
- Refactor(eos_designs): Mark flow_tracking_settings as PREVIEW for 4.7.0 by @gmuloc in https://github.com/aristanetworks/avd/pull/3789
- Refactor(eos_designs): Optional CV Pathfinder region for pathfinders by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3774
- Refactor(eos_designs): Prevent empty path-groups for auto generated WAN policies by @gmuloc in https://github.com/aristanetworks/avd/pull/3710
- Refactor(eos_designs): Remove switch-focused config from WAN Routers by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3644
- Refactor(eos_designs): Remove wan_transit and rename wan_edge to wan_router by @gmuloc in https://github.com/aristanetworks/avd/pull/3654
- Refactor(eos_designs): Rename WAN CONTROL-PLANE objects by @gmuloc in https://github.com/aristanetworks/avd/pull/3676
- Refactor(eos_designs): Set `default_underlay_routing_protocol: none` for wan_rr and wan_router by @gmuloc in https://github.com/aristanetworks/avd/pull/3775
- Refactor(eos_designs): Set cv-pathfinder interface tags for subinterfaces by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3684
- Refactor(eos_designs): Simplify WAN policies by @gmuloc in https://github.com/aristanetworks/avd/pull/3719
- Refactor(eos_designs): WAN Preview - Prefix default zone name with region name by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3688
- Refactor(eos_validate_state): ANTA Refactor AvdTestBase by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3701
- Refactor(plugins): Add option to allow duplicate primary keys in schema by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3747
- Refactor(plugins): Improve mergeonschema including more descriptive errors by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3734
- Refactor(pyavd): Add ability to detect running from source by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3632
- Refactor: Fix typo to render flow-tracking for LAN subif in WAN case by @gmuloc in https://github.com/aristanetworks/avd/pull/3729
- Refactor: Rename deploy_to_cv role and module and release as cv_deploy by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3785

Bugfixes
--------

- Fix(eos_cli_config_gen): Comply with EOS tacacs servers configuration order by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3711
- Fix(eos_cli_config_gen): Updating the valid values for PTP mode. by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3685
- Fix(eos_designs): Do not generate DP IPsec profile when HA ipsec is disabled by @gmuloc in https://github.com/aristanetworks/avd/pull/3733
- Fix(eos_designs): Make metadata cloudvision tags name case sensitive by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3771
- Fix(eos_designs): Use WAN VNI for cv-pathfinder metadata by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3728
- Fix(eos_designs): evpn_multicast error handling by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3731
- Fix(eos_validate_state): ANTA Fix the report to have consistent test descriptions, categories and input details by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3743
- Fix(plugins): Add support for python3.9 for get_all_with_path by @sugetha24 in https://github.com/aristanetworks/avd/pull/3763
- Fix(plugins): YAML Dumper/Loader not working without libyaml by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3706

New Modules
-----------

- arista.avd.cv_workflow - Deploy various objects to CloudVision

v4.6.0
======

Release Summary
---------------

Release 4.6.0 - See documentation on avd.arista.com for details.

Minor Changes
-------------

- Doc(eos_cli_config_gen): Add documentation table for Application traffic recognition by @gmuloc in https://github.com/aristanetworks/avd/pull/3449
- Doc(eos_cli_config_gen, eos_designs): Consistent descriptions for BGP AS schema fields re asdot notation by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3618
- Doc: CSS updates and mike pinning by @JulioPDX in https://github.com/aristanetworks/avd/pull/3441
- Doc: Capitalize the header for Management Interface description IPv6 in doc template by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3515
- Doc: Capitalize the header for Management Interface description in doc template by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3488
- Doc: Terminology update and minor grammar corrections by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3482
- Doc: adding more info to TerminAttr cvsourceintf by @noredistribution in https://github.com/aristanetworks/avd/pull/3580
- Doc: fix formatting for service account authentication note by @noredistribution in https://github.com/aristanetworks/avd/pull/3520
- Doc: fix mlag ibgp peering formula rendering by @noredistribution in https://github.com/aristanetworks/avd/pull/3455
- Doc: rename repo ansible-avd -> avd by @carlbuchmann in https://github.com/aristanetworks/avd/pull/3513
- Feat(deploy_to_cv): Auto onboard to I&T Studio by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3626
- Feat(eos_cli_config_gen): Add TTL max hops in router bgp by @harshitk-arista in https://github.com/aristanetworks/avd/pull/3425
- Feat(eos_cli_config_gen): Add advertise_map and supress_map keys to BGP template by @gusmb in https://github.com/aristanetworks/avd/pull/3360
- Feat(eos_cli_config_gen): Add dot1x protocol bpdu bypass by @kmueller68 in https://github.com/aristanetworks/avd/pull/3622
- Feat(eos_cli_config_gen): Add encapsulation to flow tracking by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3503
- Feat(eos_cli_config_gen): Add ipv6_attached_host_route_export for SVIs by @emilarista in https://github.com/aristanetworks/avd/pull/3564
- Feat(eos_cli_config_gen): Add path-groups keepalive interval for router path-selection by @amitsagar-arsita in https://github.com/aristanetworks/avd/pull/3501
- Feat(eos_cli_config_gen): Add pim ipv4 border router  by @philippebureau in https://github.com/aristanetworks/avd/pull/3613
- Feat(eos_cli_config_gen): Add session stats option to router bfd by @Vibhu-gslab in https://github.com/aristanetworks/avd/pull/3502
- Feat(eos_cli_config_gen): Add set_overload_bit and authentication to router_isis by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3578
- Feat(eos_cli_config_gen): Add support for MPLS resolution RIBs by @chetryan in https://github.com/aristanetworks/avd/pull/3592
- Feat(eos_cli_config_gen): Add support for flow parallelization encapsulation udp by @ayushmittal-arista in https://github.com/aristanetworks/avd/pull/3603
- Feat(eos_cli_config_gen): Add support for logging event storm-control and link-status in interfaces by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3589
- Feat(eos_cli_config_gen): Add support for monitor layer1 by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3540
- Feat(eos_cli_config_gen): Add tx-latency to queue monitor by @chetryan in https://github.com/aristanetworks/avd/pull/3364
- Feat(eos_cli_config_gen): Add vxlan_interface.Vxlan1.multicast_headend_replication by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3490
- Feat(eos_cli_config_gen): DHCP Server data model by @emilarista in https://github.com/aristanetworks/avd/pull/3269
- Feat(eos_cli_config_gen): Extend router_isis data-model by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3539
- Feat(eos_cli_config_gen): Set BFD neighbor and per-link in port-channel interfaces by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3509
- Feat(eos_cli_config_gen): Support disabling hardware encryption for ip security by @gmuloc in https://github.com/aristanetworks/avd/pull/3550
- Feat(eos_cli_config_gen): Support for setting BFD timers for BGP neighbors and peer-groups by @amitsagar-arsita in https://github.com/aristanetworks/avd/pull/3432
- Feat(eos_cli_config_gen): Support for setting default QSFP transceiver mode by @mmaaloul in https://github.com/aristanetworks/avd/pull/3271
- Feat(eos_cli_config_gen): Support for tcp mss ceiling in router path selection by @amitsagar-arsita in https://github.com/aristanetworks/avd/pull/3489
- Feat(eos_cli_config_gen): add ip verify unicast source to ethernet-, vlan- and port-channel interfaces by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3492
- Feat(eos_cli_config_gen): add router IGMP host proxy configuration support by @philippebureau in https://github.com/aristanetworks/avd/pull/3565
- Feat(eos_cli_config_gen): add sFlow sample input subinterface support by @AlexGayed in https://github.com/aristanetworks/avd/pull/3457
- Feat(eos_cli_config_gen, eos_designs): Add support for secondary ssh_key to local_users by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3514
- Feat(eos_designs): Add WAN design new top level schema keys by @gmuloc in https://github.com/aristanetworks/avd/pull/3388
- Feat(eos_designs): Add WAN interface configuration under `l3_edge.l3_interfaces` by @gmuloc in https://github.com/aristanetworks/avd/pull/3440
- Feat(eos_designs): Add l3_edge.l3_interfaces support by @gmuloc in https://github.com/aristanetworks/avd/pull/3426
- Feat(eos_designs): Add other CCS (Campus) platforms for PoE support by @jonxstill in https://github.com/aristanetworks/avd/pull/3374
- Feat(eos_designs): Add router traffic-engineering for CV Pathfinder by @gmuloc in https://github.com/aristanetworks/avd/pull/3551
- Feat(eos_designs): Add support for channel_id in l3_edge by @chetryan in https://github.com/aristanetworks/avd/pull/3585
- Feat(eos_designs): Add support for subinterfaces in nodes.l3_interfaces by @gmuloc in https://github.com/aristanetworks/avd/pull/3562
- Feat(eos_designs): Add support for virtual topologies constraints by @gmuloc in https://github.com/aristanetworks/avd/pull/3535
- Feat(eos_designs): Add the possibility to set CPU max allocation by @gmuloc in https://github.com/aristanetworks/avd/pull/3548
- Feat(eos_designs): Custom prefix length for P2P uplinks and MLAG by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3268
- Feat(eos_designs): Implement AVT policies / VRF by @gmuloc in https://github.com/aristanetworks/avd/pull/3446
- Feat(eos_designs): Inject default VRF policy with a match-all statement when missing by @gmuloc in https://github.com/aristanetworks/avd/pull/3560
- Feat(eos_designs): Interface "LACP Fallback Individual" Support by @bjmeuer in https://github.com/aristanetworks/avd/pull/3510
- Feat(eos_designs): Loopbacks data model under tenant vrfs by @emilarista in https://github.com/aristanetworks/avd/pull/3486
- Feat(eos_designs): Make maximum-path 16 default for WAN routers by @gmuloc in https://github.com/aristanetworks/avd/pull/3549
- Feat(eos_designs): Preview - Generate CV Tags and metadata for WAN by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3487
- Feat(eos_designs): Preview - Generate CV tags by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3472
- Feat(eos_designs): Set spanning-tree priority per VLAN by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3273
- Feat(eos_designs): Set static-routes on node-type l3_interfaces by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3599
- Feat(eos_designs): Single uplink to mlag pair, mlag_on_orphan_port_channel_downlink by @jrecchia1029 in https://github.com/aristanetworks/avd/pull/3495
- Feat(eos_designs): Support routing protocol option on l3_edge p2p_links by @kornoa in https://github.com/aristanetworks/avd/pull/3516
- Feat(eos_designs): Uplink p2p vrfs by @gmuloc in https://github.com/aristanetworks/avd/pull/3467
- Feat(eos_designs): WAN Preview - Generate cv_pathfinder metadata for AVTs by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3552
- Feat(eos_validate_state): ANTA Add a knob to exclude interfaces from being validated by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3576
- Feat(eos_validate_state): ANTA Bump to ANTA 0.12.0 and update code by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3575
- Feat(plugins): Preview - New arista.avd.deploy_to_cv role by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3466
- Feat: Additional fixes for Github Codespaces support by @ankudinov in https://github.com/aristanetworks/avd/pull/3519
- Feat: Avd install for codespaces by @ankudinov in https://github.com/aristanetworks/avd/pull/3476

Bugfixes
--------

- Fix(eos_cli_config_gen): Fix invalid valid value for ip_security.sa_policies.esp.encryption by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3499
- Fix(eos_cli_config_gen): Fix tables in documentation by @emilarista in https://github.com/aristanetworks/avd/pull/3525
- Fix(eos_cli_config_gen): Print config for service_routing_protocols_model ribd by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3508
- Fix(eos_cli_config_gen): Reordering router adaptive-virtual-topology / router path-selection by @gmuloc in https://github.com/aristanetworks/avd/pull/3505
- Fix(eos_cli_config_gen): Various fixes for router path-selection & application-traffic-recognition by @gmuloc in https://github.com/aristanetworks/avd/pull/3504
- Fix(eos_cli_config_gen): sa_filter.out_list generating incorrect value in router-msdp template by @CyrielRct in https://github.com/aristanetworks/avd/pull/3614
- Fix(eos_designs): Avoid in-place updates of network services impacting PyAVD by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3544
- Fix(eos_designs): Do not KeyError when no path-group is in common with pathfinder by @gmuloc in https://github.com/aristanetworks/avd/pull/3512
- Fix(eos_designs): Empty description under network-ports by @gmuloc in https://github.com/aristanetworks/avd/pull/3445
- Fix(eos_designs): Ensure VLAN VNIs are not rendered without network_services.l2 by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3588
- Fix(eos_designs): Faulty MLAG config generated when missing platform info by @emilarista in https://github.com/aristanetworks/avd/pull/3583
- Fix(eos_designs): Fix incorrect syntax in EVPN multicast PIM error messages by @jonxstill in https://github.com/aristanetworks/avd/pull/3456
- Fix(eos_designs): Remove WAN RR BGP peering when no common path-group by @gmuloc in https://github.com/aristanetworks/avd/pull/3594
- Fix(eos_designs): WAN Preview - Update configs to align to best practices by @ClausHolbechArista in https://github.com/aristanetworks/avd/pull/3556
- Fix(eos_designs): management interface for 750 platforms by @matthewgottlieb in https://github.com/aristanetworks/avd/pull/3558
- Fix(eos_validate_state): ANTA Decrease default logging level for tests by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3477
- Fix(eos_validate_state): ANTA Fix AvdTestBase structured_config objects by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3447
- Fix(eos_validate_state): ANTA Fix AvdTestInbandReachability to support the new inband management data model by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3581
- Fix(eos_validate_state): ANTA Fix bug when skipping specific tests of AvdTestBGP by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3498
- Fix(eos_validate_state): ANTA Handle Pydantic + Python 3.9.7 bug gracefully by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3601
- Fix(eos_validate_state): ANTA Refactor BGP test to now also support direct neighbors and IPv6 AFI by @carl-baillargeon in https://github.com/aristanetworks/avd/pull/3572
- Fix(plugins): Remove wrong 3.9 deprecation warning by @gmuloc in https://github.com/aristanetworks/avd/pull/3484
- Fix: Fixing eos_designs_unit_tests molecule scenario for node_type.l3interfaces.ip_address by @Shivani-gslab in https://github.com/aristanetworks/avd/pull/3577
- Fix: Invalid check for ansible in devcontainer by @ankudinov in https://github.com/aristanetworks/avd/pull/3608
- Fix: Minor container fixes by @ankudinov in https://github.com/aristanetworks/avd/pull/3474
- Fix: Remove devcontainer mounts to address error 16 with molecule by @ankudinov in https://github.com/aristanetworks/avd/pull/3541

New Modules
-----------

- arista.avd.deploy_to_cv - Deploy various objects to CloudVision

v4.5.0
======

Release Summary
---------------

Release 4.5.0 - See documentation on avd.arista.com for details.

Minor Changes
-------------

- Bump - Update Ansible and Python requirements (https://github.com/aristanetworks/ansible-avd/pull/3295)
- Bump - ansible collection dependencies (https://github.com/aristanetworks/ansible-avd/pull/3410)
- Doc - Fix doc generation (https://github.com/aristanetworks/ansible-avd/pull/3405)
- Doc - Fix missing flow_tracking table (https://github.com/aristanetworks/ansible-avd/pull/3307)
- Doc - Fix missing tables in eos_cli_config_gen (https://github.com/aristanetworks/ansible-avd/pull/3308)
- Doc - Improve role defaults documentation (https://github.com/aristanetworks/ansible-avd/pull/3320)
- Doc - Improve schema generated docs (https://github.com/aristanetworks/ansible-avd/pull/3321)
- Doc - Improve search (https://github.com/aristanetworks/ansible-avd/pull/3340)
- Doc - add CVaaS Regional URLs (https://github.com/aristanetworks/ansible-avd/pull/3243)
- Doc(eos_cli_config_gen) - Changed syslog hostname description (https://github.com/aristanetworks/ansible-avd/pull/3353)
- Doc(eos_cli_config_gen) - Fix table for router AVT (https://github.com/aristanetworks/ansible-avd/pull/3341)
- Doc(eos_designs) - svi_profiles do not support tags (https://github.com/aristanetworks/ansible-avd/pull/3319)
- Feat(eos_cli_config_gen) - Add ARP static entries (https://github.com/aristanetworks/ansible-avd/pull/3288)
- Feat(eos_cli_config_gen) - Add CRL support for management security (https://github.com/aristanetworks/ansible-avd/pull/3420)
- Feat(eos_cli_config_gen) - Add WRED support (https://github.com/aristanetworks/ansible-avd/pull/3192)
- Feat(eos_cli_config_gen) - Add additional-path for evpn address-family peer-groups (https://github.com/aristanetworks/ansible-avd/pull/3278)
- Feat(eos_cli_config_gen) - Add enabled flag to router traffic-engineering (https://github.com/aristanetworks/ansible-avd/pull/3280)
- Feat(eos_cli_config_gen) - Add ethernet interface dhcp server config (https://github.com/aristanetworks/ansible-avd/pull/3231)
- Feat(eos_cli_config_gen) - Add hardware_offload feature to flow_tracking.sampled (https://github.com/aristanetworks/ansible-avd/pull/3318)
- Feat(eos_cli_config_gen) - Add knob to define port in GNMI transport grpc (https://github.com/aristanetworks/ansible-avd/pull/3245)
- Feat(eos_cli_config_gen) - Add mtu to Dps interfaces (https://github.com/aristanetworks/ansible-avd/pull/3274)
- Feat(eos_cli_config_gen) - Add options to stun client and server (https://github.com/aristanetworks/ansible-avd/pull/3383)
- Feat(eos_cli_config_gen) - Add other valid_values for event-handler trigger 'on-boot' (https://github.com/aristanetworks/ansible-avd/pull/3264)
- Feat(eos_cli_config_gen) - Add profile and policy in adaptive-virtual-topology (https://github.com/aristanetworks/ansible-avd/pull/3351)
- Feat(eos_cli_config_gen) - Add router path-selection feature (https://github.com/aristanetworks/ansible-avd/pull/3203)
- Feat(eos_cli_config_gen) - Add support for logging format rfc5424 (https://github.com/aristanetworks/ansible-avd/pull/3386)
- Feat(eos_cli_config_gen) - Add support for qos map exp (https://github.com/aristanetworks/ansible-avd/pull/3204)
- Feat(eos_cli_config_gen) - Adding application traffic recognition model (https://github.com/aristanetworks/ansible-avd/pull/3350)
- Feat(eos_cli_config_gen) - Adding options for path-selection lb policies (https://github.com/aristanetworks/ansible-avd/pull/3334)
- Feat(eos_cli_config_gen) - Deprecate daemon_terminattr.cvcompression (https://github.com/aristanetworks/ansible-avd/pull/3275)
- Feat(eos_cli_config_gen) - Extend CLI model for ip_security (https://github.com/aristanetworks/ansible-avd/pull/3312)
- Feat(eos_cli_config_gen) - Extend sbfd for initiator measurement round-trip (https://github.com/aristanetworks/ansible-avd/pull/3347)
- Feat(eos_cli_config_gen) - Implement NAT profiles + ethernet interfaces CLI (https://github.com/aristanetworks/ansible-avd/pull/3294)
- Feat(eos_cli_config_gen) - Implement VRRP for ethernet interfaces (https://github.com/aristanetworks/ansible-avd/pull/3276)
- Feat(eos_cli_config_gen) - Implement management-ssh client-alive (https://github.com/aristanetworks/ansible-avd/pull/3265)
- Feat(eos_cli_config_gen) - Implement platform sfe cpu allocation maximum (https://github.com/aristanetworks/ansible-avd/pull/3287)
- Feat(eos_cli_config_gen) - Implement speed for management interfaces (https://github.com/aristanetworks/ansible-avd/pull/3284)
- Feat(eos_cli_config_gen) - Improve generated documentation (https://github.com/aristanetworks/ansible-avd/pull/3377)
- Feat(eos_cli_config_gen) - LLDP for Management interfaces (https://github.com/aristanetworks/ansible-avd/pull/3277)
- Feat(eos_cli_config_gen) - Support Sand MDB Profiles (https://github.com/aristanetworks/ansible-avd/pull/3372)
- Feat(eos_cli_config_gen) - Support for "agents" config (https://github.com/aristanetworks/ansible-avd/pull/3282)
- Feat(eos_cli_config_gen) - Support of next_hop_unchanged under EVPN address family (https://github.com/aristanetworks/ansible-avd/pull/3232)
- Feat(eos_cli_config_gen) - implement global ip dhcp snooping (https://github.com/aristanetworks/ansible-avd/pull/3323)
- Feat(eos_cli_config_gen) - router adaptive-virtual-topology (https://github.com/aristanetworks/ansible-avd/pull/3237)
- Feat(eos_cli_config_gen) - support for mlag peer-link requests disabled under dhcp_relay (https://github.com/aristanetworks/ansible-avd/pull/3262)
- Feat(eos_cli_config_gen,eos_designs) - Add support for 'l2 mru' (https://github.com/aristanetworks/ansible-avd/pull/3164)
- Feat(eos_designs) - Add RD and RT override for VRFs (https://github.com/aristanetworks/ansible-avd/pull/3419)
- Feat(eos_designs) - Add `default_mgmt_method` to be used later in new management settings. (https://github.com/aristanetworks/ansible-avd/pull/3328)
- Feat(eos_designs) - Add ntp_settings (https://github.com/aristanetworks/ansible-avd/pull/3293)
- Feat(eos_designs) - Add uplink_type at nodes level (https://github.com/aristanetworks/ansible-avd/pull/3385)
- Feat(eos_designs) - Added the is_deployed knob to the structured_config (https://github.com/aristanetworks/ansible-avd/pull/3241)
- Feat(eos_designs) - Improve custom python class API for interface descriptions (https://github.com/aristanetworks/ansible-avd/pull/3311)
- Feat(eos_designs) - Phone VLAN support for endpoints (https://github.com/aristanetworks/ansible-avd/pull/3317)
- Feat(eos_designs) - Port-channel ID knob for uplinks with type "port-channel" (https://github.com/aristanetworks/ansible-avd/pull/3176)
- Feat(eos_designs) - Support PTP on MLAG peer-link (https://github.com/aristanetworks/ansible-avd/pull/3040)
- Feat(eos_designs) - Support for PIM RP access_list_name under VRFs and Tenants (https://github.com/aristanetworks/ansible-avd/pull/3201)
- Feat(eos_designs) - Support for underlay uplink_switch_interface_speed (https://github.com/aristanetworks/ansible-avd/pull/3256)
- Feat(eos_designs,eos_cli_config_gen) - Add metadata.platform to structured configuration (https://github.com/aristanetworks/ansible-avd/pull/3421)
- Feat(eos_validate_state) - ANTA Add eAPI HTTPS SSL profile test (https://github.com/aristanetworks/ansible-avd/pull/3357)
- Feat(eos_validate_state) - ANTA New action plugin to generate the reports (https://github.com/aristanetworks/ansible-avd/pull/3352)
- Refactor(eos_designs) - Add testcases for ipaddressing and move it to plugin utils (https://github.com/aristanetworks/ansible-avd/pull/2410)
- Refactor(eos_designs) - Optimize conversion of structured config outputs (https://github.com/aristanetworks/ansible-avd/pull/3240)
- Refactor(eos_designs) - Remove EVPN limitation for underlay_filter_peer_as (https://github.com/aristanetworks/ansible-avd/pull/3207)
- Refactor(eos_designs) - Reorder BGP address family rendering for overlay module (https://github.com/aristanetworks/ansible-avd/pull/3393)

Bugfixes
--------

- Fix(cvp_configlet_upload) - Use correct var for tasks manipulation (https://github.com/aristanetworks/ansible-avd/pull/3337)
- Fix(eos_cli_config_gen) - Add device documentation for phone VLAN features (https://github.com/aristanetworks/ansible-avd/pull/3329)
- Fix(eos_cli_config_gen) - Add line delimiter at beginning of ip access-list cli (https://github.com/aristanetworks/ansible-avd/pull/3403)
- Fix(eos_cli_config_gen) - Correct syntax for "redistribute bgp" in router bgp (https://github.com/aristanetworks/ansible-avd/pull/3369)
- Fix(eos_cli_config_gen) - Fix radius attribute 32 format option. (https://github.com/aristanetworks/ansible-avd/pull/3413)
- Fix(eos_cli_config_gen) - Hide ip-security shared-key from device documentation (https://github.com/aristanetworks/ansible-avd/pull/3411)
- Fix(eos_cli_config_gen) - MAC Security key fallback configured even if set to false (https://github.com/aristanetworks/ansible-avd/pull/3437)
- Fix(eos_cli_config_gen) - Merge flow_tracking tables (https://github.com/aristanetworks/ansible-avd/pull/3396)
- Fix(eos_cli_config_gen) - Missing password key in router_bgp.neighbors.items (https://github.com/aristanetworks/ansible-avd/pull/3326)
- Fix(eos_cli_config_gen) - Render switchport mode for all modes for Port-channels (https://github.com/aristanetworks/ansible-avd/pull/3429)
- Fix(eos_cli_config_gen) - STUN server supports multiple local interfaces (https://github.com/aristanetworks/ansible-avd/pull/3266)
- Fix(eos_cli_config_gen) - Wrong CLI template for some ip_security options (https://github.com/aristanetworks/ansible-avd/pull/3263)
- Fix(eos_cli_config_gen) - correct logging event storm-control unter interface ethernet (https://github.com/aristanetworks/ansible-avd/pull/3303)
- Fix(eos_cli_config_gen) - l2_mtu under port_channel_interfaces (https://github.com/aristanetworks/ansible-avd/pull/3291)
- Fix(eos_cli_config_gen, eos_designs) - BGP VRF Prefix-lists not allowed outside of AF (https://github.com/aristanetworks/ansible-avd/pull/3358)
- Fix(eos_cli_config_gen,eos_designs) - Accept numeric ACL names (https://github.com/aristanetworks/ansible-avd/pull/3363)
- Fix(eos_config_deploy_cvp) - share tags from parent to dependent tasks. (https://github.com/aristanetworks/ansible-avd/pull/3333)
- Fix(eos_designs) - Handling empty vars in network services (https://github.com/aristanetworks/ansible-avd/pull/3314)
- Fix(eos_designs) - Include ISIS interfaces in fabric docs if any device uses ISIS (https://github.com/aristanetworks/ansible-avd/pull/3345)
- Fix(eos_designs) - Incorect type for bpg remote_as (https://github.com/aristanetworks/ansible-avd/pull/3313)
- Fix(eos_designs) - Inherited structured_config on multiple SVIs. (https://github.com/aristanetworks/ansible-avd/pull/3298)
- Fix(eos_validate_state) - ANTA Add a check to AvdTestLLDPTopology for shutdown interfaces (https://github.com/aristanetworks/ansible-avd/pull/3234)
- Fix(eos_validate_state) - ANTA Add conditions to skip tests if a device is not deployed (https://github.com/aristanetworks/ansible-avd/pull/3272)
- Fix(eos_validate_state) - ANTA Adding support for FQDN Ansible hosts and fix errors when shutdown and description keys are missing (https://github.com/aristanetworks/ansible-avd/pull/3407)

New Modules
-----------

- arista.avd.eos_validate_state_reports - Generates validation reports for the eos_validate_state role

v4.4.0
======

Release Summary
---------------

Release 4.4.0 - See documentation on avd.arista.com for details.

Minor Changes
-------------

- Doc - Add updated requirements for jsonschema in 4.2.0 by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3157)
- Doc - Add updated requirements to release-notes for 3.8.x train by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3155)
- Doc - Automatic generation of docs for collection plugins by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/3061)
- Doc - Custom templates docs by @andsouth44 in (https://github.com/aristanetworks/ansible-avd/pull/3150)
- Doc - Reorder schema tables with dynamic keys first by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/3216)
- Doc - Update AVD project maintainers by @carlbuchmann in (https://github.com/aristanetworks/ansible-avd/pull/3196)
- Doc(eos_cli_config_gen) - Fix spacing in router-bgp documentation template by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3197)
- Doc(eos_designs) - Clarify evpn_multicast required for evpn_l2/l3_multicast by @jonxstill in (https://github.com/aristanetworks/ansible-avd/pull/3156)
- Feat - Support inline comments in requirements.txt by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3125)
- Feat(eos_cli_config_gen) - Add 'router service-insertion' CLI by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3220)
- Feat(eos_cli_config_gen) - Add Dps1 interface by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3198)
- Feat(eos_cli_config_gen) - Add ECN Support by @chetryan in (https://github.com/aristanetworks/ansible-avd/pull/2770)
- Feat(eos_cli_config_gen) - Add IPv4 and IPv6 SR-TE address families by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3217)
- Feat(eos_cli_config_gen) - Add ip security by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3194)
- Feat(eos_cli_config_gen) - Add support for BGP link-state address-family by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3211)
- Feat(eos_cli_config_gen) - Add support for flow tracking hardware by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3199)
- Feat(eos_cli_config_gen) - Ethernet interfaces ip address dhcp support by @carlbuchmann in (https://github.com/aristanetworks/ansible-avd/pull/3229)
- Feat(eos_cli_config_gen) - Implement next-hop resolution disabled for evpn address-family by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3218)
- Feat(eos_cli_config_gen) - Support STUN by @burnyd in (https://github.com/aristanetworks/ansible-avd/pull/3147)
- Feat(eos_cli_config_gen) - Support of a global tacacs timeout by @mmaaloul in (https://github.com/aristanetworks/ansible-avd/pull/3173)
- Feat(eos_cli_config_gen) - Support of route-target route-map for BGP VRFs by @mmaaloul in (https://github.com/aristanetworks/ansible-avd/pull/3222)
- Feat(eos_cli_config_gen) - Support path-selection bgp address-family by @burnyd in (https://github.com/aristanetworks/ansible-avd/pull/3151)
- Feat(eos_cli_config_gen) - add system l1 support by @carlbuchmann in (https://github.com/aristanetworks/ansible-avd/pull/3221)
- Feat(eos_config_deploy_cvp) - Add support for device_inventory_mode by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/2561)
- Feat(eos_designs) - Add default_interface_mtu and feature_support.per_interface_mtu by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/3128)
- Feat(eos_designs) - Build AVD topology from CloudVision I&T Studio data by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/3223)
- Feat(eos_designs) - EVPN vlan-aware-bundle option for l2vlan  by @bjmeuer in (https://github.com/aristanetworks/ansible-avd/pull/3075)
- Feat(eos_designs) - Enhance SNMP support by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/3083)
- Feat(eos_designs) - Support multiple descriptions in connected_endpoint adapters by @pvinci-arista in (https://github.com/aristanetworks/ansible-avd/pull/2966)
- Feat(eos_designs) - VTEP override option on node-definitions by @emilarista in (https://github.com/aristanetworks/ansible-avd/pull/3133)
- Feat(eos_validate_state) - Add ANTA integration to eos_validate_state role by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3171)
- Feat(plugins) - Add deprecation for ansible-core<2.14 and python 3.8 by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3187)

Bugfixes
--------

- Fix - ip reachability test with l3dge endpoint not managed by AVD by @spangoli-arista in (https://github.com/aristanetworks/ansible-avd/pull/3140)
- Fix(eos_cli_config_gen) - Correct max TTL values for ip_access_lists and ptp by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/3225)
- Fix(eos_cli_config_gen) - Correct schema for class-maps vlans and cos options by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/3215)
- Fix(eos_cli_config_gen) - Remove requirement for MACSec license and FIPS by @xaviramon in (https://github.com/aristanetworks/ansible-avd/pull/3239)
- Fix(eos_cli_config_gen) - ip http client source interfaces cli not generated by @carlbuchmann in (https://github.com/aristanetworks/ansible-avd/pull/3180)
- Fix(eos_cli_config_gen) - under maximum_paths, ecmp field is not required by @mmaaloul in (https://github.com/aristanetworks/ansible-avd/pull/3111)
- Fix(eos_config_deploy_cvp) - Avoid duplicate AVD configlet by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/3124)
- Fix(eos_designs) - Configuration of PTP for port-channel uplinks by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/3112)
- Fix(eos_designs) - Configure evpn_ebgp_gateway_multihop for ipvpn_gateway EBGP peers by @ClausHolbechArista in (https://github.com/aristanetworks/ansible-avd/pull/3205)
- Fix(eos_designs) - Improve evpn_multicast error handling by @jonxstill in (https://github.com/aristanetworks/ansible-avd/pull/3195)
- Fix(eos_designs) - change speed group value from int to str by @philippebureau in (https://github.com/aristanetworks/ansible-avd/pull/3235)
- Fix(eos_designs) - removed min and max value from vrf_id by @karnag3 in (https://github.com/aristanetworks/ansible-avd/pull/3130)
- Fix(eos_validate_state) - ANTA VerifyRoutingProtocolModel now only run if there is BGP configuration by @carl-baillargeon in (https://github.com/aristanetworks/ansible-avd/pull/3212)
- Fix(plugins) - Raise AnsibleFilterError when range is invalid by @gmuloc in (https://github.com/aristanetworks/ansible-avd/pull/3163)

New Modules
-----------

- arista.avd.eos_validate_state_runner - Leverage ANTA for eos_validate_state role

v4.3.0
======

Release Summary
---------------

Release 4.2.0 - See documentation on avd.arista.com for details.

Minor Changes
-------------

- Bump - Add support for Ansible 2.15.x (https://github.com/aristanetworks/ansible-avd/pull/3070)
- Doc - Add license header to YAML source files. (https://github.com/aristanetworks/ansible-avd/pull/3099)
- Doc - Insert license header in all source files (https://github.com/aristanetworks/ansible-avd/pull/3092)
- Doc - Minor typo fixes on internal notes documentation (https://github.com/aristanetworks/ansible-avd/pull/3093)
- Doc - avd to cvaas (https://github.com/aristanetworks/ansible-avd/pull/3089)
- Feat(eos_cli_config_gen) - Add Trident MMU queue (https://github.com/aristanetworks/ansible-avd/pull/2835)
- Feat(eos_cli_config_gen) - Add priority flow control to qos profile (https://github.com/aristanetworks/ansible-avd/pull/2796)
- Feat(eos_cli_config_gen) - Add support for "include leaked" under BGP redistribution (https://github.com/aristanetworks/ansible-avd/pull/3071)
- Feat(eos_cli_config_gen) - Add support for ftp/tftp/telnet client source interfaces (https://github.com/aristanetworks/ansible-avd/pull/3080)
- Feat(eos_cli_config_gen) - Allow TCAM profile local file configuration (https://github.com/aristanetworks/ansible-avd/pull/2833)
- Feat(eos_cli_config_gen) - Support accounting logging (https://github.com/aristanetworks/ansible-avd/pull/3091)
- Feat(eos_cli_config_gen) - add dot1x unauthorized access/native vlan membership egress to ethernet interfaces (https://github.com/aristanetworks/ansible-avd/pull/3073)
- Feat(eos_designs) - Add control for redistribution of MLAG peering subnet (https://github.com/aristanetworks/ansible-avd/pull/3069)
- Feat(eos_designs) - Add support for setting source-interfaces for management protocols (https://github.com/aristanetworks/ansible-avd/pull/3072)
- Feat(eos_designs) - Validation of structured_config (https://github.com/aristanetworks/ansible-avd/pull/3077)
- Refactor(eos_designs) - Deprecate cvp_instance_ip in favor of cvp_instance_ips (https://github.com/aristanetworks/ansible-avd/pull/3028)
- Refactor(eos_designs) - Optimize connected endpoints temp data storage (https://github.com/aristanetworks/ansible-avd/pull/3094)

Bugfixes
--------

- Fix(eos_designs) - Don't require "mlag_peer_l3_ipv4_pool" with full rfc5549 (https://github.com/aristanetworks/ansible-avd/pull/3106)
- Fix(eos_designs) - Ensure consistent ordering of underlay route-maps (https://github.com/aristanetworks/ansible-avd/pull/3105)
- Fix(eos_designs) - Fix schema for BGP peers to allow shutdown key (https://github.com/aristanetworks/ansible-avd/pull/3100)

v4.2.0
======

Release Summary
---------------

Release 4.2.0 - See documentation on avd.arista.com for details.

Minor Changes
-------------

- Bump - Pre-release v4.2.0-dev1 (https://github.com/aristanetworks/ansible-avd/pull/3032)
- Bump - Pre-release v4.2.0-dev2 (https://github.com/aristanetworks/ansible-avd/pull/3060)
- Doc(eos_designs, eos_cli_config_gen) - Various doc improvements (https://github.com/aristanetworks/ansible-avd/pull/3001)
- Feat(dhcp_provisioner) - Adding support for automatic dict_to_list conversion in ztp_configuration template (https://github.com/aristanetworks/ansible-avd/pull/3012)
- Feat(eos_cli_config_gen) - Add global logging event storm-control (https://github.com/aristanetworks/ansible-avd/pull/2994)
- Feat(eos_cli_config_gen) - Add support for eos_cli under router_ospf process ids (https://github.com/aristanetworks/ansible-avd/pull/3035)
- Feat(eos_cli_config_gen) - ECN Propagation (https://github.com/aristanetworks/ansible-avd/pull/2841)
- Feat(eos_cli_config_gen) - Flow tracking table size (https://github.com/aristanetworks/ansible-avd/pull/2838)
- Feat(eos_cli_config_gen) - Generate sFlow egress commands (https://github.com/aristanetworks/ansible-avd/pull/2767)
- Feat(eos_cli_config_gen) - add support for password complexity policies (https://github.com/aristanetworks/ansible-avd/pull/2991)
- Feat(eos_designs) - Adding structured_config to l3_edge P2P_links (https://github.com/aristanetworks/ansible-avd/pull/3017)
- Feat(eos_designs) - Fabric IP Addressing MLAG same_subnet addressing algorithm (https://github.com/aristanetworks/ansible-avd/pull/2987)
- Feat(eos_designs) - Sflow configuration at fabric level (https://github.com/aristanetworks/ansible-avd/pull/2775)
- Feat(eos_designs,eos_cli_config_gen) - Add hostname to structured configuration (https://github.com/aristanetworks/ansible-avd/pull/3016)
- Feat(plugins) - Make setting of switch fact optional for yaml_templates_to_facts (https://github.com/aristanetworks/ansible-avd/pull/3022)
- Refactor - Adjust pyavd API and requirements (https://github.com/aristanetworks/ansible-avd/pull/3018)
- Refactor(eos_designs) - Combine core_interfaces and l3_edge python_modules (https://github.com/aristanetworks/ansible-avd/pull/3003)
- Refactor(eos_designs) - Deprecating port_channel.short_esi under connected_endpoints (https://github.com/aristanetworks/ansible-avd/pull/3027)
- Refactor(eos_designs) - Using common method for raising duplicate detection error in python_modules (https://github.com/aristanetworks/ansible-avd/pull/3033)

Bugfixes
--------

- Fix(eos_cli_config_gen) - Fix router_isis.instance schema (https://github.com/aristanetworks/ansible-avd/pull/3050)
- Fix(eos_cli_config_gen) - Fixing management_api_http.protocol_https_certificate error (https://github.com/aristanetworks/ansible-avd/pull/3023)
- Fix(eos_cli_config_gen) - Force domain_identifier to be a string (https://github.com/aristanetworks/ansible-avd/pull/2997)
- Fix(eos_cli_config_gen) - Relax schema for empty prefix-lists (https://github.com/aristanetworks/ansible-avd/pull/3008)
- Fix(eos_cli_config_gen) - Support vars on play via `vars` or `vars_files` (https://github.com/aristanetworks/ansible-avd/pull/2999)
- Fix(eos_config_deploy_cvp) - device_filter is not behaving correctly if input is a string (https://github.com/aristanetworks/ansible-avd/pull/3046)
- Fix(eos_designs) - Duplicate neighbor_interfaces in rfc5549 design when multiple uplinks to the same Spine (https://github.com/aristanetworks/ansible-avd/pull/3054)
- Fix(eos_designs) - Incorrect type for ospf.area in network services keys (https://github.com/aristanetworks/ansible-avd/pull/2998)

v4.1.0
======

Release Summary
---------------

Release 4.1.0 - See documentation on avd.arista.com for details.

Minor Changes
-------------

- Feat(eos_cli_config_gen) - Add OSPF default_information_originate options (https://github.com/aristanetworks/ansible-avd/pull/2896)
- Feat(eos_cli_config_gen) - Add comments to queue (https://github.com/aristanetworks/ansible-avd/pull/2864)
- Feat(eos_cli_config_gen) - Add trust and chain certificate (https://github.com/aristanetworks/ansible-avd/pull/2804)
- Feat(eos_designs) - Add support for POE settings under connected endpoints by @jrecchia1029 in (https://github.com/aristanetworks/ansible-avd/pull/2975)
- Feat(eos_designs) - Compact MLAG allocations (https://github.com/aristanetworks/ansible-avd/pull/2946)
- Feat(eos_designs) - Enhance RD/RT assignments options (https://github.com/aristanetworks/ansible-avd/pull/2893)
- Feat(eos_designs) - Make BFD configurable under bgp_peer_groups (https://github.com/aristanetworks/ansible-avd/pull/2890)
- Feat(eos_designs) - Support for underlay_multicast RPs and Anycast-RP (https://github.com/aristanetworks/ansible-avd/pull/2846)
- Feat(eos_designs) - Support setting "ptp.auto_clock_identity to false" as group/hostvar (https://github.com/aristanetworks/ansible-avd/pull/2815)

Bugfixes
--------

- Fix(cvp_configlet_upload) - Add requirements checks (https://github.com/aristanetworks/ansible-avd/pull/2990)
- Fix(eos_designs) - Schema validation for connected endpoints not executed (https://github.com/aristanetworks/ansible-avd/pull/2984)
- Fix(eos_designs) - Sort internal objects for consistent output (https://github.com/aristanetworks/ansible-avd/pull/2988)

v4.0.0
======

Release Summary
---------------

Release 4.0.0 - See documentation on avd.sh for details.

Minor Changes
-------------

- Bump - Cap ansible-lint to <6.14 (https://github.com/aristanetworks/ansible-avd/pull/2595)
- Bump - Collection requirements and cvprac (https://github.com/aristanetworks/ansible-avd/pull/2956)
- Bump - Pre-release 4.0.0-rc2 (https://github.com/aristanetworks/ansible-avd/pull/2905)
- Bump - Pre-release 4.0.0-rc3 (https://github.com/aristanetworks/ansible-avd/pull/2965)
- Bump - Pre-release v4.0.0-dev1 (https://github.com/aristanetworks/ansible-avd/pull/2471)
- Bump - Pre-release v4.0.0-dev10 (https://github.com/aristanetworks/ansible-avd/pull/2721)
- Bump - Pre-release v4.0.0-dev11 (https://github.com/aristanetworks/ansible-avd/pull/2769)
- Bump - Pre-release v4.0.0-dev12 (https://github.com/aristanetworks/ansible-avd/pull/2830)
- Bump - Pre-release v4.0.0-dev2 (https://github.com/aristanetworks/ansible-avd/pull/2487)
- Bump - Pre-release v4.0.0-dev3 (https://github.com/aristanetworks/ansible-avd/pull/2524)
- Bump - Pre-release v4.0.0-dev4 (https://github.com/aristanetworks/ansible-avd/pull/2546)
- Bump - Pre-release v4.0.0-dev5 (https://github.com/aristanetworks/ansible-avd/pull/2574)
- Bump - Pre-release v4.0.0-dev6 (https://github.com/aristanetworks/ansible-avd/pull/2602)
- Bump - Pre-release v4.0.0-dev7 (https://github.com/aristanetworks/ansible-avd/pull/2637)
- Bump - Pre-release v4.0.0-dev8 (https://github.com/aristanetworks/ansible-avd/pull/2662)
- Bump - Pre-release v4.0.0-dev9 (https://github.com/aristanetworks/ansible-avd/pull/2681)
- Bump - Pre-release v4.0.0-rc1 (https://github.com/aristanetworks/ansible-avd/pull/2872)
- Bump - Release notes for v3.8.1 (https://github.com/aristanetworks/ansible-avd/pull/2462)
- Bump - Update ansible-core requirement to ">=2.12.6, <2.15, !=2.13.0" (https://github.com/aristanetworks/ansible-avd/pull/2400)
- Bump - Update galaxy.yml to 4.0.0-dev0 (https://github.com/aristanetworks/ansible-avd/pull/2361)
- Bump(requirements - Remove direct dependency of `ansible.netcommon` collection (https://github.com/aristanetworks/ansible-avd/pull/2801)
- Bump(requirements) - ansible.utils to ">=2.9.0" (https://github.com/aristanetworks/ansible-avd/pull/2740)
- Cut - Remove globally defined defaults for underlay_routing_protocol and overlay_routing_protocol variables (https://github.com/aristanetworks/ansible-avd/pull/2691)
- Cut - Remove upgrade tools for 2.x to 3.0 upgrade (https://github.com/aristanetworks/ansible-avd/pull/2368)
- Cut(eos_designs) - Remove unused overlay jinja2 templates (https://github.com/aristanetworks/ansible-avd/pull/2363)
- Doc - Add a warning to upgrade the python reqs when upgrading AVD (https://github.com/aristanetworks/ansible-avd/pull/2498)
- Doc - Add details on data model changes to RN and porting-guide (https://github.com/aristanetworks/ansible-avd/pull/2977)
- Doc - Add release notes for 3.8.0 (https://github.com/aristanetworks/ansible-avd/pull/2378)
- Doc - Adding mike version provider to requirements and mkdocs (https://github.com/aristanetworks/ansible-avd/pull/2971)
- Doc - Changelog for release v3.8.0 (https://github.com/aristanetworks/ansible-avd/pull/2414)
- Doc - Fix typo in batch_template documentation (https://github.com/aristanetworks/ansible-avd/pull/2668)
- Doc - Fix typo in custom structured configuration documentation example (https://github.com/aristanetworks/ansible-avd/pull/2807)
- Doc - Fix typo in plugins README.md -arista (https://github.com/aristanetworks/ansible-avd/pull/2495)
- Doc - Gather role documentation in a single file per role (https://github.com/aristanetworks/ansible-avd/pull/2873)
- Doc - Grammar corrections on contribution guides (https://github.com/aristanetworks/ansible-avd/pull/2973)
- Doc - Minor updates to campus readme (https://github.com/aristanetworks/ansible-avd/pull/2943)
- Doc - Navigation fix and bump mkdocs-material version (https://github.com/aristanetworks/ansible-avd/pull/2536)
- Doc - Pinned mkdocs-material version and updated make (https://github.com/aristanetworks/ansible-avd/pull/2788)
- Doc - Porting guide updates (https://github.com/aristanetworks/ansible-avd/pull/2945)
- Doc - Release notes v3.8.5 (https://github.com/aristanetworks/ansible-avd/pull/2736)
- Doc - Release notes v3.8.6 (https://github.com/aristanetworks/ansible-avd/pull/2827)
- Doc - Update Dual DC L3LS example (https://github.com/aristanetworks/ansible-avd/pull/2904)
- Doc - Update Single DC L3LS example (https://github.com/aristanetworks/ansible-avd/pull/2803)
- Doc - Update campus-fabric example data model to AVD-4.0.0 -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2913)
- Doc - Update l2ls example data model to 4.0.0 (https://github.com/aristanetworks/ansible-avd/pull/2908)
- Doc - Update l3ls dual dc example data model to 4.0.0 -gslab (https://github.com/aristanetworks/ansible-avd/pull/2919)
- Doc - Update single-dc-l3ls example data model to 4.0.0 -gslab (https://github.com/aristanetworks/ansible-avd/pull/2914)
- Doc - Updated l2ls example readme with new data models (https://github.com/aristanetworks/ansible-avd/pull/2944)
- Doc - Updating the landing page, move the collection below AVD umbrella (https://github.com/aristanetworks/ansible-avd/pull/2587)
- Doc - Various documentation fixes (https://github.com/aristanetworks/ansible-avd/pull/2877)
- Doc - release notes 3.8.2 (https://github.com/aristanetworks/ansible-avd/pull/2542)
- Doc - release notes 3.8.3 (https://github.com/aristanetworks/ansible-avd/pull/2588)
- Doc - release notes v3.8.4 (https://github.com/aristanetworks/ansible-avd/pull/2649)
- Doc(eos_cli_config_gen) - Deprecate old keys under gNMI (https://github.com/aristanetworks/ansible-avd/pull/2876)
- Doc(eos_cli_config_gen) - Update site navigation with new schemas (https://github.com/aristanetworks/ansible-avd/pull/2427)
- Doc(eos_designs) - Add connected_endpoints fabric documentation (https://github.com/aristanetworks/ansible-avd/pull/2458)
- Doc(eos_designs) - Dual DC example (https://github.com/aristanetworks/ansible-avd/pull/2326)
- Doc(eos_designs) - ISIS-LDP IPVPN Topology Example (https://github.com/aristanetworks/ansible-avd/pull/2759)
- Doc(eos_designs) - Size recommendations for mlag_peer ip pools (https://github.com/aristanetworks/ansible-avd/pull/2599)
- Doc(eos_designs) - Update documentation layout (https://github.com/aristanetworks/ansible-avd/pull/2960)
- Doc(eos_designs,eos_cli_config_gen) - Add missing deprecation warnings (https://github.com/aristanetworks/ansible-avd/pull/2957)
- Doc(plugins) - Fix plugin name in BGP example (https://github.com/aristanetworks/ansible-avd/pull/2601)
- Doc(plugins) - Fix quotes in BGP password example (https://github.com/aristanetworks/ansible-avd/pull/2597)
- Feat(eos_cli_config_gen) - Add 'route_reflector_client' key to BGP neighbor in VRF (https://github.com/aristanetworks/ansible-avd/pull/2551)
- Feat(eos_cli_config_gen) - Add Sflow config for ethernet and port_channel interfaces (https://github.com/aristanetworks/ansible-avd/pull/1805)
- Feat(eos_cli_config_gen) - Add aaa authorization policy and dynamic (https://github.com/aristanetworks/ansible-avd/pull/2440)
- Feat(eos_cli_config_gen) - Add address locking options on ethernet interfaces (https://github.com/aristanetworks/ansible-avd/pull/2564)
- Feat(eos_cli_config_gen) - Add arp learning bridged (https://github.com/aristanetworks/ansible-avd/pull/2383)
- Feat(eos_cli_config_gen) - Add capability to hide passwords and keys in generated doc and conf (https://github.com/aristanetworks/ansible-avd/pull/2806)
- Feat(eos_cli_config_gen) - Add eos_cli key to management_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2379)
- Feat(eos_cli_config_gen) - Add ethernet_interfaces logging event options (https://github.com/aristanetworks/ansible-avd/pull/2783)
- Feat(eos_cli_config_gen) - Add global IP NAT support (https://github.com/aristanetworks/ansible-avd/pull/2747)
- Feat(eos_cli_config_gen) - Add interface IP NAT support (https://github.com/aristanetworks/ansible-avd/pull/2750)
- Feat(eos_cli_config_gen) - Add ipv6 dhcp relay to vlan/ethernet-interfaces (https://github.com/aristanetworks/ansible-avd/pull/2585)
- Feat(eos_cli_config_gen) - Add port-channel esi and rt deprecation warnings (https://github.com/aristanetworks/ansible-avd/pull/2443)
- Feat(eos_cli_config_gen) - Add service-policy qos (https://github.com/aristanetworks/ansible-avd/pull/2793)
- Feat(eos_cli_config_gen) - Add support for "ip_igmp_version" under "vlan_interfaces" (https://github.com/aristanetworks/ansible-avd/pull/2792)
- Feat(eos_cli_config_gen) - Add support for BGP session tracking (https://github.com/aristanetworks/ansible-avd/pull/2659)
- Feat(eos_cli_config_gen) - Add support for CVX as VXLAN controller (https://github.com/aristanetworks/ansible-avd/pull/2657)
- Feat(eos_cli_config_gen) - Add support for PoE configurations 1029 (https://github.com/aristanetworks/ansible-avd/pull/2690)
- Feat(eos_cli_config_gen) - Add support for as-path options for BGP neighbors (https://github.com/aristanetworks/ansible-avd/pull/2591)
- Feat(eos_cli_config_gen) - Add support for bgp default ipv4-unicast under router bgp (https://github.com/aristanetworks/ansible-avd/pull/2789)
- Feat(eos_cli_config_gen) - Add support for grpc-tunnel (https://github.com/aristanetworks/ansible-avd/pull/2696)
- Feat(eos_cli_config_gen) - Add support for load-interval on Ethernet Interfaces -Arista (https://github.com/aristanetworks/ansible-avd/pull/2428)
- Feat(eos_cli_config_gen) - Add support for passive BGP neighbor (https://github.com/aristanetworks/ansible-avd/pull/2568)
- Feat(eos_cli_config_gen) - Add support for shell for local users (https://github.com/aristanetworks/ansible-avd/pull/2581)
- Feat(eos_cli_config_gen) - Allow configuration of IGMP snooping features even if globally disabled (https://github.com/aristanetworks/ansible-avd/pull/2686)
- Feat(eos_cli_config_gen) - BGP RR preserve-attributes (https://github.com/aristanetworks/ansible-avd/pull/2879)
- Feat(eos_cli_config_gen) - CVX Client non-default VRF support (https://github.com/aristanetworks/ansible-avd/pull/2545)
- Feat(eos_cli_config_gen) - Default queue-monitor thresholds (https://github.com/aristanetworks/ansible-avd/pull/2794)
- Feat(eos_cli_config_gen) - Deprecation of 'vlan_interfaces.ipv6_address_virtual' (singular) (https://github.com/aristanetworks/ansible-avd/pull/2613)
- Feat(eos_cli_config_gen) - Enable redistribution of leaked (static, connected, bgp) routes into OSPF -baillargeon (https://github.com/aristanetworks/ansible-avd/pull/2639)
- Feat(eos_cli_config_gen) - Extend aaa_accounting with options for dot1x (https://github.com/aristanetworks/ansible-avd/pull/2450)
- Feat(eos_cli_config_gen) - Global IP Locking Configuration Options (https://github.com/aristanetworks/ansible-avd/pull/2560)
- Feat(eos_cli_config_gen) - L2 Protocol Forwarding (https://github.com/aristanetworks/ansible-avd/pull/2676)
- Feat(eos_cli_config_gen) - New improved ip_name_servers and deprecate name_server (https://github.com/aristanetworks/ansible-avd/pull/2738)
- Feat(eos_cli_config_gen) - Support ND parameters inside router_l2_vpn the same as ARP (https://github.com/aristanetworks/ansible-avd/pull/2538)
- Feat(eos_cli_config_gen) - Support encapsulation for EVPN peer groups (https://github.com/aristanetworks/ansible-avd/pull/2540)
- Feat(eos_cli_config_gen) - Trim documentation output to only show configured sections (https://github.com/aristanetworks/ansible-avd/pull/2357)
- Feat(eos_cli_config_gen) - add certs method to cvauth in TerminAttr (https://github.com/aristanetworks/ansible-avd/pull/2699)
- Feat(eos_cli_config_gen) - add cvsourceintf flag to TerminAttr (https://github.com/aristanetworks/ansible-avd/pull/2620)
- Feat(eos_cli_config_gen) - add event-handler trigger "on-startup-config" (https://github.com/aristanetworks/ansible-avd/pull/2486)
- Feat(eos_cli_config_gen) - add options tagged and untagged phone to switchport phone trunk for ethernet interfaces 68 (https://github.com/aristanetworks/ansible-avd/pull/2832)
- Feat(eos_cli_config_gen) - extend dot1x with radius av-pair and mac based authentication. (https://github.com/aristanetworks/ansible-avd/pull/2446)
- Feat(eos_cli_config_gen) - extend ethernet_interface with dot1x eapol authentication_failure_falback (https://github.com/aristanetworks/ansible-avd/pull/2482)
- Feat(eos_cli_config_gen) - extend radius_servers with attribute 32 include in access and dynamic-authorization (https://github.com/aristanetworks/ansible-avd/pull/2523)
- Feat(eos_config_deploy_cvp) - Option for deploying using serial number as identifier (https://github.com/aristanetworks/ansible-avd/pull/2718)
- Feat(eos_designs) - Add Ipv6 management variables (https://github.com/aristanetworks/ansible-avd/pull/2335)
- Feat(eos_designs) - Add `is_deployed` & `mgmt_interface_description` to schema (https://github.com/aristanetworks/ansible-avd/pull/2858)
- Feat(eos_designs) - Add hardware_counters schema (https://github.com/aristanetworks/ansible-avd/pull/2856)
- Feat(eos_designs) - Add per MACVRF EVPN domain scope 85 (https://github.com/aristanetworks/ansible-avd/pull/2347)
- Feat(eos_designs) - Add schema for ptp_profiles (https://github.com/aristanetworks/ansible-avd/pull/2847)
- Feat(eos_designs) - Add schema for queue_monitor_length (https://github.com/aristanetworks/ansible-avd/pull/2897)
- Feat(eos_designs) - Add schema validation to eos_designs action plugins (https://github.com/aristanetworks/ansible-avd/pull/2350)
- Feat(eos_designs) - Add support for TerminAttr token-secure auth for on-premise CV (https://github.com/aristanetworks/ansible-avd/pull/2685)
- Feat(eos_designs) - Add support for overlay_routing_protocol CVX (https://github.com/aristanetworks/ansible-avd/pull/2600)
- Feat(eos_designs) - Add support for serial_number (https://github.com/aristanetworks/ansible-avd/pull/2645)
- Feat(eos_designs) - Add support for setting "mlag_domain_id" (https://github.com/aristanetworks/ansible-avd/pull/2791)
- Feat(eos_designs) - Adding schemas for eos_designs missing keys -gslab (https://github.com/aristanetworks/ansible-avd/pull/2862)
- Feat(eos_designs) - Allow LACP timers configuration under connected_endpoints (https://github.com/aristanetworks/ansible-avd/pull/2809)
- Feat(eos_designs) - Allow disabling filtering on redist connected in underlay bgp (https://github.com/aristanetworks/ansible-avd/pull/2586)
- Feat(eos_designs) - Allow to redistribute connected routes under OSPF (https://github.com/aristanetworks/ansible-avd/pull/2762)
- Feat(eos_designs) - Fabric variable to set bgp distance (https://github.com/aristanetworks/ansible-avd/pull/2869)
- Feat(eos_designs) - Improve CVX Overlay support (https://github.com/aristanetworks/ansible-avd/pull/2656)
- Feat(eos_designs) - Only require 'virtual_router_mac_address' when using VARP or anycast IP on SVIs (https://github.com/aristanetworks/ansible-avd/pull/2485)
- Feat(eos_designs) - Schema for CVP (https://github.com/aristanetworks/ansible-avd/pull/2509)
- Feat(eos_designs) - Schema for connected endpoints (https://github.com/aristanetworks/ansible-avd/pull/2505)
- Feat(eos_designs) - Schema for custom structured configuration (https://github.com/aristanetworks/ansible-avd/pull/2508)
- Feat(eos_designs) - Schema for default interfaces (https://github.com/aristanetworks/ansible-avd/pull/2512)
- Feat(eos_designs) - Schema for evpn (https://github.com/aristanetworks/ansible-avd/pull/2514)
- Feat(eos_designs) - Schema for isis (https://github.com/aristanetworks/ansible-avd/pull/2515)
- Feat(eos_designs) - Schema for l3_edge and core_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2516)
- Feat(eos_designs) - Schema for management (https://github.com/aristanetworks/ansible-avd/pull/2513)
- Feat(eos_designs) - Schema for network services (https://github.com/aristanetworks/ansible-avd/pull/2506)
- Feat(eos_designs) - Schema for node_type (https://github.com/aristanetworks/ansible-avd/pull/2517)
- Feat(eos_designs) - Schema for overlay (https://github.com/aristanetworks/ansible-avd/pull/2518)
- Feat(eos_designs) - Schema for platforms (https://github.com/aristanetworks/ansible-avd/pull/2519)
- Feat(eos_designs) - Schema for routing (https://github.com/aristanetworks/ansible-avd/pull/2507)
- Feat(eos_designs) - Schema for topology (https://github.com/aristanetworks/ansible-avd/pull/2510)
- Feat(eos_designs) - Schema for underlay (https://github.com/aristanetworks/ansible-avd/pull/2520)
- Feat(eos_designs) - Support for custom masks in core_interfaces ip pools (https://github.com/aristanetworks/ansible-avd/pull/2469)
- Feat(eos_designs) - Support for custom masks in l3_edge ip pools (https://github.com/aristanetworks/ansible-avd/pull/2466)
- Feat(eos_designs) - Uplink native vlan for l2 switches (https://github.com/aristanetworks/ansible-avd/pull/2522)
- Feat(eos_designs) - User defined description on management interface (https://github.com/aristanetworks/ansible-avd/pull/2500)
- Feat(eos_designs) - User defined descriptions on l3_edge and core_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2499)
- Feat(eos_designs) - update PTP syntax "enable" -> "enabled" (https://github.com/aristanetworks/ansible-avd/pull/2776)
- Feat(eos_designs) - use proper structured config knobs for bgp maximum paths (https://github.com/aristanetworks/ansible-avd/pull/2868)
- Feat(plugins) - Add OSPF pasword type 7 to encrypt/decrypt filters (https://github.com/aristanetworks/ansible-avd/pull/2626)
- Feat(plugins) - Add arista.avd.batch_template action plugin (https://github.com/aristanetworks/ansible-avd/pull/2593)
- Feat(plugins) - Add arista.avd.global_vars plugin (https://github.com/aristanetworks/ansible-avd/pull/2751)
- Feat(plugins) - Add schema driven deprecation warnings (https://github.com/aristanetworks/ansible-avd/pull/2369)
- Feat(plugins) - Add sections in schema-based docs (https://github.com/aristanetworks/ansible-avd/pull/2969)
- Feat(plugins) - Automatic requirements check (https://github.com/aristanetworks/ansible-avd/pull/2015)
- Feat(plugins) - Make 'dest' optional on 'validate_and_template' (https://github.com/aristanetworks/ansible-avd/pull/2423)
- Feat(plugins) - Schema support for 'convert_to_lower_case' (https://github.com/aristanetworks/ansible-avd/pull/2688)
- Feat(plugins) - Support for importlib.metadata multi dist detection (https://github.com/aristanetworks/ansible-avd/pull/2614)
- Feat(plugins) - Update schema validation to ignore any key starting with underscore (https://github.com/aristanetworks/ansible-avd/pull/2689)
- Refactor - Change $def to $defs (https://github.com/aristanetworks/ansible-avd/pull/2734)
- Refactor - Input data conversion to support conversion messages (https://github.com/aristanetworks/ansible-avd/pull/2349)
- Refactor(eos_cli_config_gen - Add guards for missing name for hardware_counters legacy syntax (https://github.com/aristanetworks/ansible-avd/pull/2741)
- Refactor(eos_cli_config_gen - Deprecate uppercase `MIB_family_name` in favor of `mib_family_name` (https://github.com/aristanetworks/ansible-avd/pull/2772)
- Refactor(eos_cli_config_gen, eos_designs - Improve BGP VRF Address Families Model (https://github.com/aristanetworks/ansible-avd/pull/2808)
- Refactor(eos_cli_config_gen,eos_designs) - Deprecate isis_af_defaults and address_family knobs (https://github.com/aristanetworks/ansible-avd/pull/2630)
- Refactor(eos_cli_config_gen,eos_designs) - Remove multiple H1 headings (https://github.com/aristanetworks/ansible-avd/pull/2632)
- Refactor(eos_designs) - Add "shared_utils" and optimize code (https://github.com/aristanetworks/ansible-avd/pull/2708)
- Refactor(eos_designs) - Auto-convert eos_designs output according to schema (https://github.com/aristanetworks/ansible-avd/pull/2381)
- Refactor(eos_designs) - Change default native vlan name (https://github.com/aristanetworks/ansible-avd/pull/2563)
- Refactor(eos_designs) - Change description for port-channel members to be the physical peer interface instead of port-channel -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2949)
- Refactor(eos_designs) - Improve code reuse in parsing of connected endpoints (https://github.com/aristanetworks/ansible-avd/pull/2633)
- Refactor(eos_designs) - Move default variables to python instead of role defaults. (https://github.com/aristanetworks/ansible-avd/pull/2760)
- Refactor(eos_designs) - New plugin eos_designs_structured_config instead of yaml_templates_to_facts (https://github.com/aristanetworks/ansible-avd/pull/2857)
- Refactor(eos_designs) - Optimize and fix switch facts (https://github.com/aristanetworks/ansible-avd/pull/2678)
- Refactor(eos_designs) - Relax requirement for 'id' if not used (https://github.com/aristanetworks/ansible-avd/pull/2661)
- Refactor(eos_designs) - Remove template data from avd_switch_facts (https://github.com/aristanetworks/ansible-avd/pull/2687)
- Refactor(eos_designs) - Remove vxlan_vlan_aware_bundles in favor of evpn_vlan_aware_bundles -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2865)
- Refactor(eos_designs) - Return list-based data models from eos_designs python modules - MLAG -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2831)
- Refactor(eos_designs) - Use natural_sort instead of sorted everywhere (https://github.com/aristanetworks/ansible-avd/pull/2384)
- Refactor(eos_designs) - Use python for all default interface descriptions (https://github.com/aristanetworks/ansible-avd/pull/2490)
- Refactor(eos_designs) - base python_module as per eos_cli_config_gen 34 (https://github.com/aristanetworks/ansible-avd/pull/2624)
- Refactor(eos_designs) - ethernet_interfaces python module as per eos_cli_config_gen -gslab (https://github.com/aristanetworks/ansible-avd/pull/2627)
- Refactor(eos_designs) - loopback_interfaces python_module as per eos_ci_config_gen -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2598)
- Refactor(eos_designs) - network_services/ip_igmp_snooping python_module as per eos_cli_config_gen -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2554)
- Refactor(eos_designs) - port_channel_interfaces python_module as per eos_cli_config_gen -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2609)
- Refactor(eos_designs) - prefix_lists python_module as per eos_cli_config_gen -gslab (https://github.com/aristanetworks/ansible-avd/pull/2555)
- Refactor(eos_designs) - route_maps, vrfs, ip_ext_community_lists and struct_cfgs python_module as per eos_cli_config_gen -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2567)
- Refactor(eos_designs) - router_bgp python_module as per eos_cli_config_gen -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2625)
- Refactor(eos_designs) - router_ospf python_module as per eos_cli_config_gen -gslab (https://github.com/aristanetworks/ansible-avd/pull/2559)
- Refactor(eos_designs) - schema auto documentation template (https://github.com/aristanetworks/ansible-avd/pull/2571)
- Refactor(eos_designs) - vlan_interfaces python_module as per eos_cli_config_gen -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2592)
- Refactor(eos_designs) - vlans, virtual_source_nat_vrfs python_modules as per eos_cli_config_gen 34 (https://github.com/aristanetworks/ansible-avd/pull/2577)
- Refactor(eos_designs) - vxlan_interface, management_interfaces python_modules as per eos_cli_config_gen -gslab (https://github.com/aristanetworks/ansible-avd/pull/2584)
- Refactor(eos_designs, eos_cli_config_gen - BGP VRF peer group options, global context ipv6 multicast and flowspec (https://github.com/aristanetworks/ansible-avd/pull/2976)
- Refactor(plugins) - Add ability raise on missing dependencies in validator (https://github.com/aristanetworks/ansible-avd/pull/2501)
- Refactor(plugins) - Improvements of schema tools preparing for eos_designs schemas (https://github.com/aristanetworks/ansible-avd/pull/2437)
- Refactor(plugins) - Optimize convert_dicts (https://github.com/aristanetworks/ansible-avd/pull/2810)
- Refactor(plugins) - Optimize loading of schemas (https://github.com/aristanetworks/ansible-avd/pull/2575)
- Refactor(plugins) - Optimize schema tooling (https://github.com/aristanetworks/ansible-avd/pull/2672)
- Revert(eos_designs - Revert enabling of graceful-restart by default (https://github.com/aristanetworks/ansible-avd/pull/2958)
- Revert(eos_validate_state) - Revert removal of error=ignore on lookups (https://github.com/aristanetworks/ansible-avd/pull/2468)

Breaking Changes / Porting Guide
--------------------------------

- Bump(cvp_configlet_upload,eos_config_deploy_cvp)! - Update the default `cv_collection` from `v1` to `v3` (https://github.com/aristanetworks/ansible-avd/pull/2882)
- Feat(eos_cli_config_gen)! - Change Hardware Counter model (https://github.com/aristanetworks/ansible-avd/pull/2695)
- Feat(eos_config_deploy_cvp)! - Support for dynamic inventories (https://github.com/aristanetworks/ansible-avd/pull/2395)
- Feat(eos_designs)! - Change p2p_uplinks_mtu default value from 9000 to 9214 (https://github.com/aristanetworks/ansible-avd/pull/2844)
- Feat(eos_designs)! - Enhance inband management configuration options -arista (https://github.com/aristanetworks/ansible-avd/pull/2712)
- Feat(eos_designs)! - Platform and Fabric variables to adjust update wait-for-convergence and update wait-install (https://github.com/aristanetworks/ansible-avd/pull/2855)
- Feat(eos_designs)! - Remove default value from mlag_peer_link_allowed_vlans (https://github.com/aristanetworks/ansible-avd/pull/2845)
- Feat(eos_designs)! - fabric variable for bgp default ipv4 unicast (https://github.com/aristanetworks/ansible-avd/pull/2799)
- Feat(eos_designs, eos_cli_config_gen)! - Remove default "switchport" and remove logic from eos_cli_config_gen (https://github.com/aristanetworks/ansible-avd/pull/2430)
- Feat(eos_designs,eos_cli_config_gen)! - bgp graceful-restart (https://github.com/aristanetworks/ansible-avd/pull/2842)
- Fix! - Change uppercase CVP role vars to lower case (https://github.com/aristanetworks/ansible-avd/pull/2504)
- Fix(eos_designs)! - Prevent configuration of IP routing on l2leaf (https://github.com/aristanetworks/ansible-avd/pull/2684)
- Fix(eos_designs)! - Remove BGP rendering on irrelevant nodes (https://github.com/aristanetworks/ansible-avd/pull/2774)
- Refactor(eos_cli_config_gen)! - Require `enabled true` under `vlan_interfaces.[].ip_attached_host_route_export` (https://github.com/aristanetworks/ansible-avd/pull/2773)
- Refactor(eos_cli_config_gen)! - Require queue_monitor_length.enabled to be set -chourasiya (https://github.com/aristanetworks/ansible-avd/pull/2429)

Bugfixes
--------

- Fix - Description key not considered with connected endpoints -arista (https://github.com/aristanetworks/ansible-avd/pull/2745)
- Fix - Formatting to pass latest galaxy-importer and ansible-lint rules (https://github.com/aristanetworks/ansible-avd/pull/2445)
- Fix - Logging buffered default level not required (https://github.com/aristanetworks/ansible-avd/pull/2364)
- Fix - add guard to dot1x mac_based_authentication -arista (https://github.com/aristanetworks/ansible-avd/pull/2764)
- Fix(eos_cli_config_gen) -  Workaround for router-general EOS CLI issue (https://github.com/aristanetworks/ansible-avd/pull/2408)
- Fix(eos_cli_config_gen) - Add convert_types to router ospf area id schema (https://github.com/aristanetworks/ansible-avd/pull/2391)
- Fix(eos_cli_config_gen) - Add variable protection for router_bgp.as in doc template (https://github.com/aristanetworks/ansible-avd/pull/2503)
- Fix(eos_cli_config_gen) - Checks for missing "vlans" key on access port-channel (https://github.com/aristanetworks/ansible-avd/pull/2701)
- Fix(eos_cli_config_gen) - Correct schema min values for terminal length/width (https://github.com/aristanetworks/ansible-avd/pull/2481)
- Fix(eos_cli_config_gen) - Ensure unique VRF names in schemas (https://github.com/aristanetworks/ansible-avd/pull/2878)
- Fix(eos_cli_config_gen) - Fix documentation template for flow tracking (https://github.com/aristanetworks/ansible-avd/pull/2636)
- Fix(eos_cli_config_gen) - Fix the router_multicast vrfs indentation (https://github.com/aristanetworks/ansible-avd/pull/2476)
- Fix(eos_cli_config_gen) - Fix typo in router-bgp.j2 (https://github.com/aristanetworks/ansible-avd/pull/2753)
- Fix(eos_cli_config_gen) - Relax schema for maintenance unit profile (https://github.com/aristanetworks/ansible-avd/pull/2492)
- Fix(eos_cli_config_gen) - Render LLDP commands on ethernet_interfaces also for port-channel members (https://github.com/aristanetworks/ansible-avd/pull/2386)
- Fix(eos_cli_config_gen) - Update Schema for OSPF maximum paths from 32 to 128 -Arista (https://github.com/aristanetworks/ansible-avd/pull/2424)
- Fix(eos_cli_config_gen) - Update radius-server and radius-servers to match EOS behavior (https://github.com/aristanetworks/ansible-avd/pull/2615)
- Fix(eos_cli_config_gen) - Update schema for logging (https://github.com/aristanetworks/ansible-avd/pull/2553)
- Fix(eos_cli_config_gen) - Update schema for storm_control levels to support int or float (https://github.com/aristanetworks/ansible-avd/pull/2562)
- Fix(eos_cli_config_gen) - min value on local_users privilege (https://github.com/aristanetworks/ansible-avd/pull/2617)
- Fix(eos_cli_config_gen,eos_designs) - Update schemas missing `items` and remove unused keys (https://github.com/aristanetworks/ansible-avd/pull/2892)
- Fix(eos_designs) - Add back dir creation wrongly removed by PR 2015 (https://github.com/aristanetworks/ansible-avd/pull/2622)
- Fix(eos_designs) - Add mlag_ibgp_origin_incomplete in eos_designs schema (https://github.com/aristanetworks/ansible-avd/pull/2716)
- Fix(eos_designs) - Add support for her and cvx in default_overlay_routing_protocol (https://github.com/aristanetworks/ansible-avd/pull/2717)
- Fix(eos_designs) - Avoid configuring trunk-group twice on mlag peer-link if using the same name (https://github.com/aristanetworks/ansible-avd/pull/2658)
- Fix(eos_designs) - Change IP addressing templates from ansible netcommon to ansible.utils (https://github.com/aristanetworks/ansible-avd/pull/2677)
- Fix(eos_designs) - Change authentication method and token path for on-prem token auth (https://github.com/aristanetworks/ansible-avd/pull/2800)
- Fix(eos_designs) - Configure "ip routing ipv6 interface vrf X" for RFC5549 (https://github.com/aristanetworks/ansible-avd/pull/2660)
- Fix(eos_designs) - Configure "ipv6 enable" on SVIs with Anycast IPv6 (https://github.com/aristanetworks/ansible-avd/pull/2784)
- Fix(eos_designs) - Configure ptp to use the system mac (https://github.com/aristanetworks/ansible-avd/pull/2647)
- Fix(eos_designs) - Correct range_expand behaviour with .0 4byte ASNs (https://github.com/aristanetworks/ansible-avd/pull/2529)
- Fix(eos_designs) - Correct schema descriptions for raw_eos_cli and structured_config under network services (https://github.com/aristanetworks/ansible-avd/pull/2898)
- Fix(eos_designs) - Detect duplicate VLAN, VRF, VNI within network_services (https://github.com/aristanetworks/ansible-avd/pull/2411)
- Fix(eos_designs) - Duplicate port-channels in structured-config for network-ports (https://github.com/aristanetworks/ansible-avd/pull/2651)
- Fix(eos_designs) - Duplicate route-maps generated when using underlay_filter_peer_as true (https://github.com/aristanetworks/ansible-avd/pull/2612)
- Fix(eos_designs) - Ensure deterministic behavior when defining the same VRF in multiple Tenants (https://github.com/aristanetworks/ansible-avd/pull/2900)
- Fix(eos_designs) - Ensure proper formatting of raised errors (https://github.com/aristanetworks/ansible-avd/pull/2578)
- Fix(eos_designs) - Fix and test custom python modules for ip addressing and interface descriptions (https://github.com/aristanetworks/ansible-avd/pull/2664)
- Fix(eos_designs) - Fix error with dotted hostname, l2leaf and mlag (https://github.com/aristanetworks/ansible-avd/pull/2502)
- Fix(eos_designs) - Fix issue with hardware_counters python code (https://github.com/aristanetworks/ansible-avd/pull/2447)
- Fix(eos_designs) - Fix schema for storm_control and endpoint_ports under adapters (https://github.com/aristanetworks/ansible-avd/pull/2967)
- Fix(eos_designs) - Fix wrong error message for duplicates network_ports (https://github.com/aristanetworks/ansible-avd/pull/2756)
- Fix(eos_designs) - Handle overlapping VLAN names for l2vlans and vlan-aware-bundles (https://github.com/aristanetworks/ansible-avd/pull/2388)
- Fix(eos_designs) - Handle overlapping vlan numbers with filter.only_in_use and trunkgroups (https://github.com/aristanetworks/ansible-avd/pull/2628)
- Fix(eos_designs) - Ignore "overlay_routing_protocol_address_family ipv6" on l2leaf (https://github.com/aristanetworks/ansible-avd/pull/2955)
- Fix(eos_designs) - Improve error message for missing device facts (https://github.com/aristanetworks/ansible-avd/pull/2813)
- Fix(eos_designs) - Invalid defaults for ipvpn_gateway domain IDs (https://github.com/aristanetworks/ansible-avd/pull/2739)
- Fix(eos_designs) - Raise correct error message for duplicate port-channels (https://github.com/aristanetworks/ansible-avd/pull/2674)
- Fix(eos_designs) - Re-add the possibility to overwrite network_ports (https://github.com/aristanetworks/ansible-avd/pull/2766)
- Fix(eos_designs) - Remove EVPN related config if VRF 'default' is not EVPN enabled (https://github.com/aristanetworks/ansible-avd/pull/2888)
- Fix(eos_designs) - Renders lacp fallback when port-channel mode is passive (https://github.com/aristanetworks/ansible-avd/pull/2448)
- Fix(eos_designs) - Replace sorted with natural_sort in overlay/utils.py (https://github.com/aristanetworks/ansible-avd/pull/2374)
- Fix(eos_designs) - Schema validation in eos_designs_facts (https://github.com/aristanetworks/ansible-avd/pull/2948)
- Fix(eos_designs) - Support 4.0 data models in Connected Endpoints docs (https://github.com/aristanetworks/ansible-avd/pull/2915)
- Fix(eos_designs) - bgp_mesh_pes (https://github.com/aristanetworks/ansible-avd/pull/2899)
- Fix(eos_designs) - connected endpoints interface mode valid values (https://github.com/aristanetworks/ansible-avd/pull/2758)
- Fix(eos_designs) - eBGP rfc5549 creates invalid configuration for MLAG scenarios (https://github.com/aristanetworks/ansible-avd/pull/2950)
- Fix(eos_designs) - network services vlan interfaces ospf authentication message-digest (https://github.com/aristanetworks/ansible-avd/pull/2727)
- Fix(eos_designs) - overlay_rd_type with inline jinja generates incorrect config (https://github.com/aristanetworks/ansible-avd/pull/2393)
- Fix(eos_designs) - remove speed from port-channel interfaces (https://github.com/aristanetworks/ansible-avd/pull/2463)
- Fix(eos_designs) - vtep_vvtep_ip doesn't generate any config (https://github.com/aristanetworks/ansible-avd/pull/2442)
- Fix(eos_designs,eos_cli_config_gen) - Update schema keys for VRFs to accept numeric VRF names (https://github.com/aristanetworks/ansible-avd/pull/2979)
- Fix(eos_snapshot) - Conditional in tasks are not honored and support for limit (https://github.com/aristanetworks/ansible-avd/pull/2457)
- Fix(eos_snapshot) - Only collect cli-text commands when "text" or "markdown" are selected (https://github.com/aristanetworks/ansible-avd/pull/2439)
- Fix(eos_snapshot) - eos snapshot produces incorrect json and yaml output (https://github.com/aristanetworks/ansible-avd/pull/2426)
- Fix(plugins) - Ensure proper headings in schema generated docs (https://github.com/aristanetworks/ansible-avd/pull/2771)
- Fix(plugins) - Fix bgp_utils for ansible-test sanity and update requirements (https://github.com/aristanetworks/ansible-avd/pull/2401)
- Fix(plugins) - Fix minor schema tooling issues (https://github.com/aristanetworks/ansible-avd/pull/2870)
- Fix(plugins) - Handle git not found for verify_requirements (https://github.com/aristanetworks/ansible-avd/pull/2667)
- Fix(plugins) - Inheritance of schema documentation options (https://github.com/aristanetworks/ansible-avd/pull/2861)
- Fix(plugins) - update verify_requirements to use a color that is supported for logging (https://github.com/aristanetworks/ansible-avd/pull/2638)

New Plugins
-----------

Filter
~~~~~~

- arista.avd.hide_passwords - Replace a value by "<removed>"

Vars
~~~~

- arista.avd.global_vars - Variable plugins to allow loading global_vars with less precedence than group_vars or host_vars

New Modules
-----------

- arista.avd.batch_template - Render Jinja2 template on multiple items and write result to individual files.
- arista.avd.eos_designs_structured_config - Generate AVD EOS Designs structured configuration
- arista.avd.set_vars - Set vars as ansible_facts.
- arista.avd.verify_requirements - Verify Python requirements when running AVD

v3.8.0
======

Release Summary
---------------

Release 3.8.0 - See documentation on avd.sh for details.

Minor Changes
-------------

- Bump - Update galaxy.yml to 3.8.0-rc1 (https://github.com/aristanetworks/ansible-avd/pull/2360)
- Cut(eos_designs) - Remove unused overlay jinja2 templates (#2363) (https://github.com/aristanetworks/ansible-avd/pull/2371)
- Doc - Add Guillaume Mulocher to Maintainers (https://github.com/aristanetworks/ansible-avd/pull/2100)
- Doc - Campus Example (https://github.com/aristanetworks/ansible-avd/pull/2191)
- Doc - Exclude test files from site build, enable twitter, update links (https://github.com/aristanetworks/ansible-avd/pull/2238)
- Doc - L2LS Example (https://github.com/aristanetworks/ansible-avd/pull/1992)
- Doc - L3LS Example and Mkdoc Updates (https://github.com/aristanetworks/ansible-avd/pull/2055)
- Doc - Refactor landing page and installation guide (https://github.com/aristanetworks/ansible-avd/pull/2306)
- Doc - Remove display_name from schema generated docs (https://github.com/aristanetworks/ansible-avd/pull/2248)
- Doc - Role diagram support for light and dark modes (https://github.com/aristanetworks/ansible-avd/pull/2272)
- Doc(eos_cli_config_gen) - Add LACP to key_to_display_name plugin (https://github.com/aristanetworks/ansible-avd/pull/2293)
- Doc(eos_cli_config_gen) - Fix documentation for cvx.peer_hosts (https://github.com/aristanetworks/ansible-avd/pull/2358)
- Doc(eos_designs) - Addition of L2LS documentation (https://github.com/aristanetworks/ansible-avd/pull/2305)
- Feat - Add peer hosts to CVX (https://github.com/aristanetworks/ansible-avd/pull/2281)
- Feat - Schemas for input validation and documentation (https://github.com/aristanetworks/ansible-avd/pull/1888)
- Feat( eos_designs, eos_cli_config_gen) - Add "disabled" option to "local_users" (https://github.com/aristanetworks/ansible-avd/pull/2257)
- Feat(eos_cli_config_gen) -  Add macsec commands (https://github.com/aristanetworks/ansible-avd/pull/2286)
- Feat(eos_cli_config_gen) - Add "bfd" key to router_pim_sparse_mode (https://github.com/aristanetworks/ansible-avd/pull/2262)
- Feat(eos_cli_config_gen) - Add Router MSDP Data Model (https://github.com/aristanetworks/ansible-avd/pull/2278)
- Feat(eos_cli_config_gen) - Add flow tracking sampled support (https://github.com/aristanetworks/ansible-avd/pull/2270)
- Feat(eos_cli_config_gen) - Add graceful-restart support for router_bgp (https://github.com/aristanetworks/ansible-avd/pull/2296)
- Feat(eos_cli_config_gen) - Add key_type for ntp.authentication_keys (https://github.com/aristanetworks/ansible-avd/pull/2258)
- Feat(eos_cli_config_gen) - Add schema for aaa accounting (https://github.com/aristanetworks/ansible-avd/pull/2170)
- Feat(eos_cli_config_gen) - Add schema for aaa_authentication (https://github.com/aristanetworks/ansible-avd/pull/2121)
- Feat(eos_cli_config_gen) - Add schema for aaa_authorization (https://github.com/aristanetworks/ansible-avd/pull/2149)
- Feat(eos_cli_config_gen) - Add schema for aaa_root (https://github.com/aristanetworks/ansible-avd/pull/2148)
- Feat(eos_cli_config_gen) - Add schema for aaa_server_groups (https://github.com/aristanetworks/ansible-avd/pull/2168)
- Feat(eos_cli_config_gen) - Add schema for access_lists (https://github.com/aristanetworks/ansible-avd/pull/1995)
- Feat(eos_cli_config_gen) - Add schema for aliases (https://github.com/aristanetworks/ansible-avd/pull/2119)
- Feat(eos_cli_config_gen) - Add schema for arp (https://github.com/aristanetworks/ansible-avd/pull/2160)
- Feat(eos_cli_config_gen) - Add schema for as_path (https://github.com/aristanetworks/ansible-avd/pull/2125)
- Feat(eos_cli_config_gen) - Add schema for banners (https://github.com/aristanetworks/ansible-avd/pull/2117)
- Feat(eos_cli_config_gen) - Add schema for bgp_groups (https://github.com/aristanetworks/ansible-avd/pull/2079)
- Feat(eos_cli_config_gen) - Add schema for boot (https://github.com/aristanetworks/ansible-avd/pull/2189)
- Feat(eos_cli_config_gen) - Add schema for class_maps (https://github.com/aristanetworks/ansible-avd/pull/2065)
- Feat(eos_cli_config_gen) - Add schema for clock (https://github.com/aristanetworks/ansible-avd/pull/2133)
- Feat(eos_cli_config_gen) - Add schema for community_lists (https://github.com/aristanetworks/ansible-avd/pull/2018)
- Feat(eos_cli_config_gen) - Add schema for custom_templates (https://github.com/aristanetworks/ansible-avd/pull/2154)
- Feat(eos_cli_config_gen) - Add schema for cvx (https://github.com/aristanetworks/ansible-avd/pull/2186)
- Feat(eos_cli_config_gen) - Add schema for daemon terminattr (https://github.com/aristanetworks/ansible-avd/pull/2081)
- Feat(eos_cli_config_gen) - Add schema for daemons (https://github.com/aristanetworks/ansible-avd/pull/2027)
- Feat(eos_cli_config_gen) - Add schema for dhcp_relay (https://github.com/aristanetworks/ansible-avd/pull/2122)
- Feat(eos_cli_config_gen) - Add schema for dns_domain (https://github.com/aristanetworks/ansible-avd/pull/2132)
- Feat(eos_cli_config_gen) - Add schema for domain_list (https://github.com/aristanetworks/ansible-avd/pull/2179)
- Feat(eos_cli_config_gen) - Add schema for dot1x (https://github.com/aristanetworks/ansible-avd/pull/2197)
- Feat(eos_cli_config_gen) - Add schema for dynamic_prefix_lists (https://github.com/aristanetworks/ansible-avd/pull/2195)
- Feat(eos_cli_config_gen) - Add schema for enable_password (https://github.com/aristanetworks/ansible-avd/pull/2172)
- Feat(eos_cli_config_gen) - Add schema for eos_cli (https://github.com/aristanetworks/ansible-avd/pull/2123)
- Feat(eos_cli_config_gen) - Add schema for errdisable (https://github.com/aristanetworks/ansible-avd/pull/2124)
- Feat(eos_cli_config_gen) - Add schema for ethernet-interfaces (https://github.com/aristanetworks/ansible-avd/pull/2107)
- Feat(eos_cli_config_gen) - Add schema for event_handlers (https://github.com/aristanetworks/ansible-avd/pull/2037)
- Feat(eos_cli_config_gen) - Add schema for event_monitor (https://github.com/aristanetworks/ansible-avd/pull/2166)
- Feat(eos_cli_config_gen) - Add schema for generate_default_config (https://github.com/aristanetworks/ansible-avd/pull/2127)
- Feat(eos_cli_config_gen) - Add schema for generate_device_documentation (https://github.com/aristanetworks/ansible-avd/pull/2126)
- Feat(eos_cli_config_gen) - Add schema for hardware (https://github.com/aristanetworks/ansible-avd/pull/2187)
- Feat(eos_cli_config_gen) - Add schema for hardware_counters (https://github.com/aristanetworks/ansible-avd/pull/2054)
- Feat(eos_cli_config_gen) - Add schema for interface_defaults (https://github.com/aristanetworks/ansible-avd/pull/2130)
- Feat(eos_cli_config_gen) - Add schema for interface_groups (https://github.com/aristanetworks/ansible-avd/pull/2053)
- Feat(eos_cli_config_gen) - Add schema for interface_profiles (https://github.com/aristanetworks/ansible-avd/pull/2050)
- Feat(eos_cli_config_gen) - Add schema for ip_access_lists (https://github.com/aristanetworks/ansible-avd/pull/2116)
- Feat(eos_cli_config_gen) - Add schema for ip_access_lists_max_entries (https://github.com/aristanetworks/ansible-avd/pull/2300)
- Feat(eos_cli_config_gen) - Add schema for ip_community_lists (https://github.com/aristanetworks/ansible-avd/pull/2019)
- Feat(eos_cli_config_gen) - Add schema for ip_dhcp_relay (https://github.com/aristanetworks/ansible-avd/pull/2138)
- Feat(eos_cli_config_gen) - Add schema for ip_domain_lookup (https://github.com/aristanetworks/ansible-avd/pull/2029)
- Feat(eos_cli_config_gen) - Add schema for ip_extended_community_lists (https://github.com/aristanetworks/ansible-avd/pull/2024)
- Feat(eos_cli_config_gen) - Add schema for ip_extended_community_lists_regexp (https://github.com/aristanetworks/ansible-avd/pull/2044)
- Feat(eos_cli_config_gen) - Add schema for ip_hardware (https://github.com/aristanetworks/ansible-avd/pull/2200)
- Feat(eos_cli_config_gen) - Add schema for ip_http_client_source_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2147)
- Feat(eos_cli_config_gen) - Add schema for ip_icmp_redirect (https://github.com/aristanetworks/ansible-avd/pull/2139)
- Feat(eos_cli_config_gen) - Add schema for ip_igmp_snooping (https://github.com/aristanetworks/ansible-avd/pull/2049)
- Feat(eos_cli_config_gen) - Add schema for ip_radius_source_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2111)
- Feat(eos_cli_config_gen) - Add schema for ip_routing (https://github.com/aristanetworks/ansible-avd/pull/2164)
- Feat(eos_cli_config_gen) - Add schema for ip_routing_ipv6_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2171)
- Feat(eos_cli_config_gen) - Add schema for ip_ssh_client_source_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2150)
- Feat(eos_cli_config_gen) - Add schema for ip_tacacs_source_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2112)
- Feat(eos_cli_config_gen) - Add schema for ip_virtual_router_mac_address (https://github.com/aristanetworks/ansible-avd/pull/2161)
- Feat(eos_cli_config_gen) - Add schema for ipv6_access_lists (https://github.com/aristanetworks/ansible-avd/pull/2026)
- Feat(eos_cli_config_gen) - Add schema for ipv6_hardware (https://github.com/aristanetworks/ansible-avd/pull/2203)
- Feat(eos_cli_config_gen) - Add schema for ipv6_icmp_redirect (https://github.com/aristanetworks/ansible-avd/pull/2140)
- Feat(eos_cli_config_gen) - Add schema for ipv6_prefix_lists (https://github.com/aristanetworks/ansible-avd/pull/2045)
- Feat(eos_cli_config_gen) - Add schema for ipv6_standard_access_lists (https://github.com/aristanetworks/ansible-avd/pull/1998)
- Feat(eos_cli_config_gen) - Add schema for ipv6_static_routes (https://github.com/aristanetworks/ansible-avd/pull/2182)
- Feat(eos_cli_config_gen) - Add schema for ipv6_unicast_routing (https://github.com/aristanetworks/ansible-avd/pull/2165)
- Feat(eos_cli_config_gen) - Add schema for lacp (https://github.com/aristanetworks/ansible-avd/pull/2136)
- Feat(eos_cli_config_gen) - Add schema for link_tracking_groups (https://github.com/aristanetworks/ansible-avd/pull/2135)
- Feat(eos_cli_config_gen) - Add schema for lldp (https://github.com/aristanetworks/ansible-avd/pull/2134)
- Feat(eos_cli_config_gen) - Add schema for load_interval (https://github.com/aristanetworks/ansible-avd/pull/2176)
- Feat(eos_cli_config_gen) - Add schema for local_users (https://github.com/aristanetworks/ansible-avd/pull/2020)
- Feat(eos_cli_config_gen) - Add schema for logging (https://github.com/aristanetworks/ansible-avd/pull/2085)
- Feat(eos_cli_config_gen) - Add schema for loopback_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2086)
- Feat(eos_cli_config_gen) - Add schema for mac_access_lists (https://github.com/aristanetworks/ansible-avd/pull/2118)
- Feat(eos_cli_config_gen) - Add schema for mac_address_table (https://github.com/aristanetworks/ansible-avd/pull/2156)
- Feat(eos_cli_config_gen) - Add schema for mac_security (https://github.com/aristanetworks/ansible-avd/pull/2058)
- Feat(eos_cli_config_gen) - Add schema for maintenance (https://github.com/aristanetworks/ansible-avd/pull/2028)
- Feat(eos_cli_config_gen) - Add schema for management-api-http (https://github.com/aristanetworks/ansible-avd/pull/2062)
- Feat(eos_cli_config_gen) - Add schema for management-ssh (https://github.com/aristanetworks/ansible-avd/pull/2060)
- Feat(eos_cli_config_gen) - Add schema for management_api_gnmi (https://github.com/aristanetworks/ansible-avd/pull/2303)
- Feat(eos_cli_config_gen) - Add schema for management_api_models (https://github.com/aristanetworks/ansible-avd/pull/2205)
- Feat(eos_cli_config_gen) - Add schema for management_console (https://github.com/aristanetworks/ansible-avd/pull/2146)
- Feat(eos_cli_config_gen) - Add schema for management_cvx (https://github.com/aristanetworks/ansible-avd/pull/2202)
- Feat(eos_cli_config_gen) - Add schema for management_defaults (https://github.com/aristanetworks/ansible-avd/pull/2198)
- Feat(eos_cli_config_gen) - Add schema for management_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2059)
- Feat(eos_cli_config_gen) - Add schema for management_security (https://github.com/aristanetworks/ansible-avd/pull/2145)
- Feat(eos_cli_config_gen) - Add schema for management_tech_support (https://github.com/aristanetworks/ansible-avd/pull/2201)
- Feat(eos_cli_config_gen) - Add schema for match_list_input (https://github.com/aristanetworks/ansible-avd/pull/2023)
- Feat(eos_cli_config_gen) - Add schema for mcs_client (https://github.com/aristanetworks/ansible-avd/pull/2204)
- Feat(eos_cli_config_gen) - Add schema for mlag_configuration (https://github.com/aristanetworks/ansible-avd/pull/2173)
- Feat(eos_cli_config_gen) - Add schema for monitor_connectivity (https://github.com/aristanetworks/ansible-avd/pull/2174)
- Feat(eos_cli_config_gen) - Add schema for monitor_sessions (https://github.com/aristanetworks/ansible-avd/pull/2188)
- Feat(eos_cli_config_gen) - Add schema for mpls (https://github.com/aristanetworks/ansible-avd/pull/2162)
- Feat(eos_cli_config_gen) - Add schema for name_server (https://github.com/aristanetworks/ansible-avd/pull/2178)
- Feat(eos_cli_config_gen) - Add schema for ntp (https://github.com/aristanetworks/ansible-avd/pull/2151)
- Feat(eos_cli_config_gen) - Add schema for patch_panel (https://github.com/aristanetworks/ansible-avd/pull/2144)
- Feat(eos_cli_config_gen) - Add schema for peer-filters (https://github.com/aristanetworks/ansible-avd/pull/2047)
- Feat(eos_cli_config_gen) - Add schema for platform (https://github.com/aristanetworks/ansible-avd/pull/2128)
- Feat(eos_cli_config_gen) - Add schema for policy_maps (https://github.com/aristanetworks/ansible-avd/pull/2066)
- Feat(eos_cli_config_gen) - Add schema for port_channel_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2137)
- Feat(eos_cli_config_gen) - Add schema for prefix_lists (https://github.com/aristanetworks/ansible-avd/pull/2042)
- Feat(eos_cli_config_gen) - Add schema for prompt (https://github.com/aristanetworks/ansible-avd/pull/2153)
- Feat(eos_cli_config_gen) - Add schema for ptp (https://github.com/aristanetworks/ansible-avd/pull/2287)
- Feat(eos_cli_config_gen) - Add schema for qos (https://github.com/aristanetworks/ansible-avd/pull/2155)
- Feat(eos_cli_config_gen) - Add schema for qos_profiles (https://github.com/aristanetworks/ansible-avd/pull/2084)
- Feat(eos_cli_config_gen) - Add schema for queue_monitor_length (https://github.com/aristanetworks/ansible-avd/pull/2158)
- Feat(eos_cli_config_gen) - Add schema for queue_monitor_streaming (https://github.com/aristanetworks/ansible-avd/pull/2159)
- Feat(eos_cli_config_gen) - Add schema for radius_servers (https://github.com/aristanetworks/ansible-avd/pull/2114)
- Feat(eos_cli_config_gen) - Add schema for redundancy (https://github.com/aristanetworks/ansible-avd/pull/2129)
- Feat(eos_cli_config_gen) - Add schema for roles (https://github.com/aristanetworks/ansible-avd/pull/2113)
- Feat(eos_cli_config_gen) - Add schema for route_maps (https://github.com/aristanetworks/ansible-avd/pull/2048)
- Feat(eos_cli_config_gen) - Add schema for router multicast (https://github.com/aristanetworks/ansible-avd/pull/2167)
- Feat(eos_cli_config_gen) - Add schema for router-bgp (https://github.com/aristanetworks/ansible-avd/pull/2105)
- Feat(eos_cli_config_gen) - Add schema for router-pim-sparse-mode (https://github.com/aristanetworks/ansible-avd/pull/2061)
- Feat(eos_cli_config_gen) - Add schema for router_bfd (https://github.com/aristanetworks/ansible-avd/pull/2120)
- Feat(eos_cli_config_gen) - Add schema for router_general (https://github.com/aristanetworks/ansible-avd/pull/2067)
- Feat(eos_cli_config_gen) - Add schema for router_igmp (https://github.com/aristanetworks/ansible-avd/pull/2068)
- Feat(eos_cli_config_gen) - Add schema for router_isis (https://github.com/aristanetworks/ansible-avd/pull/2181)
- Feat(eos_cli_config_gen) - Add schema for router_l2_vpn (https://github.com/aristanetworks/ansible-avd/pull/2194)
- Feat(eos_cli_config_gen) - Add schema for router_ospf (https://github.com/aristanetworks/ansible-avd/pull/2077)
- Feat(eos_cli_config_gen) - Add schema for router_traffic_engineering (https://github.com/aristanetworks/ansible-avd/pull/2192)
- Feat(eos_cli_config_gen) - Add schema for service_routing_configuration_bgp (https://github.com/aristanetworks/ansible-avd/pull/2184)
- Feat(eos_cli_config_gen) - Add schema for service_routing_protocols_model (https://github.com/aristanetworks/ansible-avd/pull/2185)
- Feat(eos_cli_config_gen) - Add schema for service_unsupported_transceiver (https://github.com/aristanetworks/ansible-avd/pull/2301)
- Feat(eos_cli_config_gen) - Add schema for sflow (https://github.com/aristanetworks/ansible-avd/pull/2036)
- Feat(eos_cli_config_gen) - Add schema for sflow (https://github.com/aristanetworks/ansible-avd/pull/2056)
- Feat(eos_cli_config_gen) - Add schema for snmp_server (https://github.com/aristanetworks/ansible-avd/pull/2094)
- Feat(eos_cli_config_gen) - Add schema for spanning_tree (https://github.com/aristanetworks/ansible-avd/pull/2082)
- Feat(eos_cli_config_gen) - Add schema for standard_access_lists (https://github.com/aristanetworks/ansible-avd/pull/2022)
- Feat(eos_cli_config_gen) - Add schema for static_routes (https://github.com/aristanetworks/ansible-avd/pull/2183)
- Feat(eos_cli_config_gen) - Add schema for switchport_default (https://github.com/aristanetworks/ansible-avd/pull/2196)
- Feat(eos_cli_config_gen) - Add schema for system (https://github.com/aristanetworks/ansible-avd/pull/2143)
- Feat(eos_cli_config_gen) - Add schema for tacacs_servers (https://github.com/aristanetworks/ansible-avd/pull/2115)
- Feat(eos_cli_config_gen) - Add schema for tap_aggregation (https://github.com/aristanetworks/ansible-avd/pull/2190)
- Feat(eos_cli_config_gen) - Add schema for tcam_profile (https://github.com/aristanetworks/ansible-avd/pull/2057)
- Feat(eos_cli_config_gen) - Add schema for terminal (https://github.com/aristanetworks/ansible-avd/pull/2157)
- Feat(eos_cli_config_gen) - Add schema for trackers (https://github.com/aristanetworks/ansible-avd/pull/2199)
- Feat(eos_cli_config_gen) - Add schema for traffic-policies (https://github.com/aristanetworks/ansible-avd/pull/2083)
- Feat(eos_cli_config_gen) - Add schema for virtual_source_nat_vrfs (https://github.com/aristanetworks/ansible-avd/pull/2089)
- Feat(eos_cli_config_gen) - Add schema for vlan_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2106)
- Feat(eos_cli_config_gen) - Add schema for vlan_internal_order (https://github.com/aristanetworks/ansible-avd/pull/2041)
- Feat(eos_cli_config_gen) - Add schema for vlans (https://github.com/aristanetworks/ansible-avd/pull/2095)
- Feat(eos_cli_config_gen) - Add schema for vmtracer_sessions (https://github.com/aristanetworks/ansible-avd/pull/2046)
- Feat(eos_cli_config_gen) - Add schema for vrfs (https://github.com/aristanetworks/ansible-avd/pull/2088)
- Feat(eos_cli_config_gen) - Add schema for vxlan-interfaces (https://github.com/aristanetworks/ansible-avd/pull/2097)
- Feat(eos_cli_config_gen) - Add shutdown knob to MCS client commands (https://github.com/aristanetworks/ansible-avd/pull/2009)
- Feat(eos_cli_config_gen) - Add support for EVPN multicast ipv4 AF transit (https://github.com/aristanetworks/ansible-avd/pull/2277)
- Feat(eos_cli_config_gen) - Add support for mtu under management interface (https://github.com/aristanetworks/ansible-avd/pull/2080)
- Feat(eos_cli_config_gen) - Add support for sub-route-map and continue in route-maps (https://github.com/aristanetworks/ansible-avd/pull/1850)
- Feat(eos_cli_config_gen) - Add tunnel interface functionality (https://github.com/aristanetworks/ansible-avd/pull/2260)
- Feat(eos_cli_config_gen) - Add various config options for Sflow (https://github.com/aristanetworks/ansible-avd/pull/2249)
- Feat(eos_cli_config_gen) - Fix macsec template (https://github.com/aristanetworks/ansible-avd/pull/2297)
- Feat(eos_cli_config_gen) - MAC address on management interfaces (https://github.com/aristanetworks/ansible-avd/pull/2275)
- Feat(eos_cli_config_gen) - Source-interface for management cvx (https://github.com/aristanetworks/ansible-avd/pull/2294)
- Feat(eos_cli_config_gen) - Support access-lists & options on rp addresses (https://github.com/aristanetworks/ansible-avd/pull/2355)
- Feat(eos_cli_config_gen) - Support for MCS client commands (https://github.com/aristanetworks/ansible-avd/pull/1999)
- Feat(eos_cli_config_gen) - Support for setting queue-monitor length cpu thresholds (https://github.com/aristanetworks/ansible-avd/pull/2012)
- Feat(eos_cli_config_gen) - Support mcs cvx server commands (https://github.com/aristanetworks/ansible-avd/pull/1985)
- Feat(eos_cli_config_gen) - Support no queue-monitor length notifying (https://github.com/aristanetworks/ansible-avd/pull/2253)
- Feat(eos_cli_config_gen) - Support route_reflector_client key on BGP neighbors (https://github.com/aristanetworks/ansible-avd/pull/2298)
- Feat(eos_cli_config_gen) - add cvconfig flag to TerminAttr (https://github.com/aristanetworks/ansible-avd/pull/2217)
- Feat(eos_cli_config_gen) - add support for SSL profile cipher-list (https://github.com/aristanetworks/ansible-avd/pull/2000)
- Feat(eos_cli_config_gen, eos_designs) - Support Track BFD in static routes (https://github.com/aristanetworks/ansible-avd/pull/2320)
- Feat(eos_designs) - Add channel_id for endpoints (https://github.com/aristanetworks/ansible-avd/pull/2070)
- Feat(eos_designs) - Add support for multiple descriptions for l3_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2291)
- Feat(eos_designs) - Add support for setting node_type by matching regexes against the hostname (https://github.com/aristanetworks/ansible-avd/pull/2266)
- Feat(eos_designs) - Add support for system mac address derived engine ID (https://github.com/aristanetworks/ansible-avd/pull/2289)
- Feat(eos_designs) - Adding 7020R to plattform settings (https://github.com/aristanetworks/ansible-avd/pull/2356)
- Feat(eos_designs) - Auto BGP ASN (https://github.com/aristanetworks/ansible-avd/pull/1948)
- Feat(eos_designs) - EVPN Multicast L3 (OISM) Support (https://github.com/aristanetworks/ansible-avd/pull/2276)
- Feat(eos_designs) - EVPN to MPLS-VPN Gateway Overlay Support (https://github.com/aristanetworks/ansible-avd/pull/2209)
- Feat(eos_designs) - Optional underlay eBGP filtering of paths with peer's ASN (https://github.com/aristanetworks/ansible-avd/pull/2030)
- Feat(eos_designs) - Support for PTP configuration based on best practices (https://github.com/aristanetworks/ansible-avd/pull/1916)
- Feat(eos_designs) - Support for Static Flood Lists, HER (https://github.com/aristanetworks/ansible-avd/pull/1982)
- Feat(eos_designs) - Support for custom naming of trunk groups (https://github.com/aristanetworks/ansible-avd/pull/2021)
- Feat(eos_designs) - Support static_routes for default vrf  under network-services (https://github.com/aristanetworks/ansible-avd/pull/1986)
- Feat(eos_designs) - Support structured config under network services svis and l2vlans for bgp commands (https://github.com/aristanetworks/ansible-avd/pull/1947)
- Feat(eos_designs) - Support the ip_virtual_router_addresses and ip_address_virtual under the same svi (https://github.com/aristanetworks/ansible-avd/pull/2239)
- Feat(eos_validate_state) - custom fan & pwr states (https://github.com/aristanetworks/ansible-avd/pull/2222)
- Feat(eos_validate_state) - skip lldp topology for shutdown (https://github.com/aristanetworks/ansible-avd/pull/2221)
- Feat(plugins) - AVD to JSON Schema Converter (https://github.com/aristanetworks/ansible-avd/pull/2090)
- Feat(plugins) - Add schema support for auto-conversion of floats (https://github.com/aristanetworks/ansible-avd/pull/2247)
- Feat(plugins) - Add schema support for secondary_key (https://github.com/aristanetworks/ansible-avd/pull/2034)
- Feat(plugins) - New arista.avd.include_vars plugin (https://github.com/aristanetworks/ansible-avd/pull/2040)
- Feat(plugins,eos_cli_config_gen) - add bgp_encrypt filter bgp password (https://github.com/aristanetworks/ansible-avd/pull/2207)
- Fix(eos_designs, eos_cli_config_gen) - Fix ipv6_address_virtual and ipv6_virtual_router (https://github.com/aristanetworks/ansible-avd/pull/2141)
- Refactor - Change variable names for schema and update docs (https://github.com/aristanetworks/ansible-avd/pull/2302)
- Refactor - Jinja templating with caching (https://github.com/aristanetworks/ansible-avd/pull/2307)
- Refactor - Move python libraries to plugin_utils (https://github.com/aristanetworks/ansible-avd/pull/2032)
- Refactor - Nice print jsonschema (https://github.com/aristanetworks/ansible-avd/pull/2142)
- Refactor - Python formatting using Black and isort (https://github.com/aristanetworks/ansible-avd/pull/2098)
- Refactor(eos_cli_config_gen) - Ensure that validation always runs in eos_cli_config_gen (https://github.com/aristanetworks/ansible-avd/pull/2039)
- Refactor(eos_cli_config_gen) - Merge input validation with templating (https://github.com/aristanetworks/ansible-avd/pull/2131)
- Refactor(eos_cli_config_gen) - schema review and template organization (https://github.com/aristanetworks/ansible-avd/pull/2323)
- Refactor(eos_designs) - Layout of python packages (https://github.com/aristanetworks/ansible-avd/pull/2282)
- Refactor(eos_designs) - Move "structured_config" for "l3_edge" to python (https://github.com/aristanetworks/ansible-avd/pull/2327)
- Refactor(eos_designs) - Move IP and description logic to Python (step1) (https://github.com/aristanetworks/ansible-avd/pull/2091)
- Refactor(eos_designs) - Move Structured Config for Inband Management to Python (https://github.com/aristanetworks/ansible-avd/pull/2283)
- Refactor(eos_designs) - Move custom_structured_configuration to python (https://github.com/aristanetworks/ansible-avd/pull/2268)
- Refactor(eos_designs) - Move eos_designs structured_config templates to Python (https://github.com/aristanetworks/ansible-avd/pull/1971)
- Refactor(eos_designs) - Move structured_config for connected_endpoints to Python (https://github.com/aristanetworks/ansible-avd/pull/2322)
- Refactor(eos_designs) - Move structured_config for core_interfaces to Python (https://github.com/aristanetworks/ansible-avd/pull/2284)
- Refactor(eos_designs) - Move structured_config for overlay to Python (https://github.com/aristanetworks/ansible-avd/pull/2329)
- Refactor(eos_designs) - Move structured_config for underlay to Python (https://github.com/aristanetworks/ansible-avd/pull/2308)
- Refactor(eos_designs) - Move structured_config generation for MLAG to Python (https://github.com/aristanetworks/ansible-avd/pull/2092)
- Refactor(eos_designs) - Move structured_config generation for Network Services to Python (https://github.com/aristanetworks/ansible-avd/pull/2175)
- Refactor(eos_designs) - Optimize templating and variable handling (https://github.com/aristanetworks/ansible-avd/pull/1997)
- Refactor(eos_designs) - Underlay/Overlay internal logic refactor to better support future MPLS interworking abstraction. (https://github.com/aristanetworks/ansible-avd/pull/2109)
- Refactor(eos_designs) - Use natural_sort instead of sorted everywhere (#2384) (https://github.com/aristanetworks/ansible-avd/pull/2404)
- Refactor(eos_validate_state) - Improve performance by delagation asserts to localhost (https://github.com/aristanetworks/ansible-avd/pull/2290)
- Refactor(eos_validate_state) - Support for new data models (https://github.com/aristanetworks/ansible-avd/pull/2231)
- Refactor(plugins) - Adding support of secondary_key for nested dictionaries in convert_dicts filter (https://github.com/aristanetworks/ansible-avd/pull/2035)
- Refactor(plugins) - Data validation tooling (https://github.com/aristanetworks/ansible-avd/pull/2317)
- Revert(eos_designs) - Removing switch.x facts (https://github.com/aristanetworks/ansible-avd/pull/2152)

Bugfixes
--------

- Doc - Fix Images in Campus Fabric Example (https://github.com/aristanetworks/ansible-avd/pull/2348)
- Doc - Fix code block, update variable information (https://github.com/aristanetworks/ansible-avd/pull/2339)
- Doc - Fix incorrect key names for custom mlag interface descriptions (https://github.com/aristanetworks/ansible-avd/pull/2235)
- Doc(eos_designs) - Fix snmp_settings.compute_v3_user_localized_key typo (https://github.com/aristanetworks/ansible-avd/pull/2072)
- Doc(eos_designs) - specify that id must be unique within a node_type (https://github.com/aristanetworks/ansible-avd/pull/2014)
- Fix - Create MLAG port-channels with network_ports data model (https://github.com/aristanetworks/ansible-avd/pull/2011)
- Fix - Ensure get.avd.sh make script sets the correct UID (https://github.com/aristanetworks/ansible-avd/pull/2210)
- Fix - File permissions for documentation and schema tasks (https://github.com/aristanetworks/ansible-avd/pull/2292)
- Fix - Incorrect table rendering for L2LS (https://github.com/aristanetworks/ansible-avd/pull/2318)
- Fix - Logging buffered default level not required (#2364) (https://github.com/aristanetworks/ansible-avd/pull/2372)
- Fix - Remove ansible-test enforced GPL3 header from modules (https://github.com/aristanetworks/ansible-avd/pull/2010)
- Fix - Update json schema (https://github.com/aristanetworks/ansible-avd/pull/2099)
- Fix - pr labeler action (https://github.com/aristanetworks/ansible-avd/pull/2051)
- Fix - schema auto generated documentation and json schema (https://github.com/aristanetworks/ansible-avd/pull/2251)
- Fix(eos_cli_config_gen) - Add convert_types to router ospf area id schema (#2391) (https://github.com/aristanetworks/ansible-avd/pull/2402)
- Fix(eos_cli_config_gen) - Render LLDP commands on ethernet_interfaces also for port-channel members (#2386) (https://github.com/aristanetworks/ansible-avd/pull/2405)
- Fix(eos_cli_config_gen) - Updates to schema for policy_maps (https://github.com/aristanetworks/ansible-avd/pull/2177)
- Fix(eos_cli_config_gen) - documentation failure when enable isis on vlan-interface (https://github.com/aristanetworks/ansible-avd/pull/2076)
- Fix(eos_cli_config_gen) - make description, ip and gateway optional for management_interfaces (https://github.com/aristanetworks/ansible-avd/pull/2224)
- Fix(eos_designs) - Avoid configuring "vxlan virtual-router encapsulation mac-address mlag-system-id" when not applicable (https://github.com/aristanetworks/ansible-avd/pull/2325)
- Fix(eos_designs) - BGP Default Originate produced invalid key for route-map (https://github.com/aristanetworks/ansible-avd/pull/2108)
- Fix(eos_designs) - Create MLAG peer-group when needed for non-BGP underlays (https://github.com/aristanetworks/ansible-avd/pull/2316)
- Fix(eos_designs) - Create mgmt interface even if no gateway is set (https://github.com/aristanetworks/ansible-avd/pull/2246)
- Fix(eos_designs) - Fix core_interfaces ISIS logic (https://github.com/aristanetworks/ansible-avd/pull/2078)
- Fix(eos_designs) - Fix the router_isis redistribute_routes connected (https://github.com/aristanetworks/ansible-avd/pull/2001)
- Fix(eos_designs) - Handle overlapping VLAN names for l2vlans and vlan-aware-bundles (#2388) (https://github.com/aristanetworks/ansible-avd/pull/2389)
- Fix(eos_designs) - Minor issues in new PTP feature (https://github.com/aristanetworks/ansible-avd/pull/2331)
- Fix(eos_designs) - Missing defined check for enable_trunk_groups (https://github.com/aristanetworks/ansible-avd/pull/2038)
- Fix(eos_designs) - PTP documentation not linked from mkdocs.yml (https://github.com/aristanetworks/ansible-avd/pull/2334)
- Fix(eos_designs) - Python import error for AristaAvdMissingVariableError (https://github.com/aristanetworks/ansible-avd/pull/2295)
- Fix(eos_designs) - Remove j2caching since it is unstable between versions (https://github.com/aristanetworks/ansible-avd/pull/2351)
- Fix(eos_designs) - Replace sorted with natural_sort in overlay/utils.py (#2374) (https://github.com/aristanetworks/ansible-avd/pull/2375)
- Fix(eos_designs) - `filter.only_vlans_in_use` did not configure vlans used by `network_ports` (https://github.com/aristanetworks/ansible-avd/pull/2104)
- Fix(eos_designs) - allow ':' in the description for network_ports (https://github.com/aristanetworks/ansible-avd/pull/2225)
- Fix(eos_designs) - fix wrong type being returned for mac_address_table aging-time (https://github.com/aristanetworks/ansible-avd/pull/2103)
- Fix(eos_designs) - force inband_management_vlan as integer (https://github.com/aristanetworks/ansible-avd/pull/2345)
- Fix(eos_designs) - overlay_rd_type with inline jinja generates incorrect config (#2393) (https://github.com/aristanetworks/ansible-avd/pull/2403)
- Fix(eos_designs) - remove the need for mgmt_gateway (https://github.com/aristanetworks/ansible-avd/pull/1931)
- Fix(eos_validate_state) - Always create directory for reports (https://github.com/aristanetworks/ansible-avd/pull/2261)
- Fix(eos_validate_state) - Handle missing  interfaces, MLAG and BGP peers (https://github.com/aristanetworks/ansible-avd/pull/2330)
- Fix(plugins) - Fix bgp_utils for ansible-test sanity and update requirements (#2401) (https://github.com/aristanetworks/ansible-avd/pull/2406)

New Modules
-----------

- arista.avd.validate_and_template - Validate input data according to Schema, render Jinja2 template and write result to a file.

v3.7.0
======

Release Summary
---------------

Release 3.7.0 - See documentation on avd.sh for details.

Minor Changes
-------------

- CI - Build ci container on devel push and pr target (https://github.com/aristanetworks/ansible-avd/pull/1923)
- CI - Limit runtime (https://github.com/aristanetworks/ansible-avd/pull/1975)
- CI - Remove validation of single commit title (https://github.com/aristanetworks/ansible-avd/pull/1943)
- CI - Revert building CI containers (https://github.com/aristanetworks/ansible-avd/pull/1928)
- CI - Update CODEOWNERS after group was renamed (https://github.com/aristanetworks/ansible-avd/pull/1987)
- CI - Update to run on ubuntu 20.04 instead of 18.04 (https://github.com/aristanetworks/ansible-avd/pull/1990)
- CI - add flake8 support matching ansible-test sanity (https://github.com/aristanetworks/ansible-avd/pull/1944)
- CI - move j2lint check to pre-commit (https://github.com/aristanetworks/ansible-avd/pull/1926)
- Doc - AVD beginner TOI update to be consistent with AVD examples (https://github.com/aristanetworks/ansible-avd/pull/1908)
- Doc - Add proper installation guide links on README (https://github.com/aristanetworks/ansible-avd/pull/1915)
- Doc - Heading Updates (https://github.com/aristanetworks/ansible-avd/pull/1991)
- Doc - Minor doc changes (https://github.com/aristanetworks/ansible-avd/pull/1935)
- Doc - Update AVD Core team (https://github.com/aristanetworks/ansible-avd/pull/1920)
- Doc - mkdoc updates with layouts, font, material theme, and syntax highlighting (https://github.com/aristanetworks/ansible-avd/pull/1951)
- Doc - refactoring (https://github.com/aristanetworks/ansible-avd/pull/1952)
- Doc(eos_designs) - Add documentation for mlag_ibgp_origin_incomplete (https://github.com/aristanetworks/ansible-avd/pull/1904)
- Doc(eos_designs) - change adapters.mode to Optional (https://github.com/aristanetworks/ansible-avd/pull/1937)
- Feat - Add AVD Example single-dc-l3ls (https://github.com/aristanetworks/ansible-avd/pull/1849)
- Feat(eos_cli_config_gen) - BGP VPN-IPv4/v6 SAFI route-map and match failure discard (https://github.com/aristanetworks/ansible-avd/pull/1851)
- Feat(eos_cli_config_gen) - Enhance support for PTP monitoring (https://github.com/aristanetworks/ansible-avd/pull/1921)
- Feat(eos_cli_config_gen) - Support multicast routing under ethernet and vlan interfaces (https://github.com/aristanetworks/ansible-avd/pull/1959)
- Feat(eos_cli_config_gen) - add ip helper to Ethernet interface (https://github.com/aristanetworks/ansible-avd/pull/1844)
- Feat(eos_cli_config_gen) - add support for logging event congestion-drops (https://github.com/aristanetworks/ansible-avd/pull/1933)
- Feat(eos_cli_config_gen) - router bgp link-bandwidth (https://github.com/aristanetworks/ansible-avd/pull/1950)
- Feat(eos_designs) -  knob to enable multicast in underlay (https://github.com/aristanetworks/ansible-avd/pull/1899)
- Feat(eos_designs) - Add l2ls default node type key and template (https://github.com/aristanetworks/ansible-avd/pull/1938)
- Feat(eos_designs) - Add network_ports data model for large scale port configurations (https://github.com/aristanetworks/ansible-avd/pull/1910)
- Feat(eos_designs) - Add none as a valid value for underlay and underlay protocol (https://github.com/aristanetworks/ansible-avd/pull/1939)
- Feat(eos_designs) - Add support for trunk_groups (https://github.com/aristanetworks/ansible-avd/pull/1826)
- Feat(eos_designs) - Automatic uplink/downlink/mlag peer-link allocation (https://github.com/aristanetworks/ansible-avd/pull/1758)
- Feat(eos_designs) - BGP peer groups in VRFs (https://github.com/aristanetworks/ansible-avd/pull/1663)
- Feat(eos_designs) - Fabric EVPN multicast (https://github.com/aristanetworks/ansible-avd/pull/1922)
- Feat(eos_designs) - Native dot1x support for connected_endpoints (https://github.com/aristanetworks/ansible-avd/pull/1932)
- Feat(eos_designs) - Only configure vlans in use by connected endpoints or downstream L2 switches (https://github.com/aristanetworks/ansible-avd/pull/1821)
- Feat(eos_designs) - Single-Active EVPN Multihoming (https://github.com/aristanetworks/ansible-avd/pull/1864)
- Feat(eos_designs) - Support Pure L2 Spine in L2LS (https://github.com/aristanetworks/ansible-avd/pull/1983)
- Feat(eos_designs) - Support all keys with svi_profiles (https://github.com/aristanetworks/ansible-avd/pull/1941)
- Feat(eos_designs) - Support automatic BGP peer groups without nodes (https://github.com/aristanetworks/ansible-avd/pull/1914)
- Feat(eos_designs) - Support different ipv4 pool for mlag ibgp peerings (https://github.com/aristanetworks/ansible-avd/pull/1819)
- Feat(eos_designs) - Support for structured_config on bgp_peer_groups (https://github.com/aristanetworks/ansible-avd/pull/1905)
- Feat(eos_designs) - custom_templates_extra_vars (https://github.com/aristanetworks/ansible-avd/pull/1989)
- Feat(eos_designs) - evpn l2 multicast in network services (https://github.com/aristanetworks/ansible-avd/pull/1907)
- Feat(eos_designs) - igmp querier in network services (https://github.com/aristanetworks/ansible-avd/pull/1958)
- Feat(eos_designs) - support switch_id and offset in rd admin subfield (https://github.com/aristanetworks/ansible-avd/pull/1977)
- Refactor(eos_designs) - Wildcard dict to list for <node_type_key> (https://github.com/aristanetworks/ansible-avd/pull/1911)
- Refactor(eos_designs) - Wildcard dict to list for tenants.vrfs.svis.nodes (https://github.com/aristanetworks/ansible-avd/pull/1976)
- Refactor(eos_designs)! - MPLS Peer Logic (https://github.com/aristanetworks/ansible-avd/pull/1906)
- Refactor(plugins) - Replacing ansible combine filter with deepmerge in yaml_templates_to_facts (https://github.com/aristanetworks/ansible-avd/pull/1964)
- Test - Skip generation of fabric documentation in `EOS_DESIGNS_UNIT_TESTS` molecule scenario (https://github.com/aristanetworks/ansible-avd/pull/1912)
- Test(eos_designs) - Add molecule scenario for L2LS (https://github.com/aristanetworks/ansible-avd/pull/1972)
- Test(eos_designs) - Refactor unit tests (https://github.com/aristanetworks/ansible-avd/pull/1918)
- Test(eos_designs) - Remove invalid variables from molecule scenarios (https://github.com/aristanetworks/ansible-avd/pull/1942)

Bugfixes
--------

- Doc - Minor fixes in getting-started docs (https://github.com/aristanetworks/ansible-avd/pull/1934)
- Doc(eos_snapshot) - fix var name in input example (https://github.com/aristanetworks/ansible-avd/pull/1960)
- Fix - typos (https://github.com/aristanetworks/ansible-avd/pull/1957)
- Fix(eos_cli_config_gen) - Re-add seperator between VRF and non-VRF config (https://github.com/aristanetworks/ansible-avd/pull/1961)
- Fix(eos_cli_config_gen) - Rendering of dot1x cli (https://github.com/aristanetworks/ansible-avd/pull/1924)
- Fix(eos_cli_config_gen) - add vlan.vni var is defined (https://github.com/aristanetworks/ansible-avd/pull/1919)
- Fix(eos_cli_config_gen) - print the vlans in alphabetical order for `router bgp` (https://github.com/aristanetworks/ansible-avd/pull/1925)
- Fix(eos_designs) - Correct underlay routing for overlay_routing_protocol "none" (https://github.com/aristanetworks/ansible-avd/pull/1970)
- Fix(eos_designs) - Missing IGP no-passive for single MLAG VLAN (https://github.com/aristanetworks/ansible-avd/pull/1974)
- Fix(eos_designs) - Only configure EVPN filtering on EVPN nodes (https://github.com/aristanetworks/ansible-avd/pull/1969)
- Fix(eos_designs) - Remove unneeded mlag ibgp vlan for vrf default (https://github.com/aristanetworks/ansible-avd/pull/1968)
- Fix(eos_designs) - Resolve inline jinja in fabric_name (https://github.com/aristanetworks/ansible-avd/pull/1967)
- Fix(eos_designs) - fix logic for underlay_multicast (https://github.com/aristanetworks/ansible-avd/pull/1940)
- Fix(eos_designs) - fix the Loopback0 interface description (https://github.com/aristanetworks/ansible-avd/pull/1955)
- Fix(eos_designs) - only create igmp snooping querier configuration on l3 devices (https://github.com/aristanetworks/ansible-avd/pull/1978)
- Fix(eos_designs) - return the missing node_type in error (https://github.com/aristanetworks/ansible-avd/pull/1981)
- Test - Fix various ansible-test issues (https://github.com/aristanetworks/ansible-avd/pull/1917)

v3.6.0
======

Release Summary
---------------

Release 3.6.0 - See documentation on avd.sh for details.

Minor Changes
-------------

- CI - fix j2lint typo delimeter -> delimiter (https://github.com/aristanetworks/ansible-avd/pull/1875)
- Feat(eos_cli_config_gen) - Add ip_directed_broadcast to vlan_interfaces (https://github.com/aristanetworks/ansible-avd/pull/1896)
- Feat(eos_cli_config_gen) - Add support for OSPF BFD sessions for adjacencies in any state (https://github.com/aristanetworks/ansible-avd/pull/1830)
- Feat(eos_cli_config_gen) - Route redistribution under router isis (https://github.com/aristanetworks/ansible-avd/pull/1811)
- Feat(eos_cli_config_gen) - SBFD configuration under Router BFD and SR-TE policy (https://github.com/aristanetworks/ansible-avd/pull/1808)
- Feat(eos_cli_config_gen) - Support bfd vtep evpn commands (https://github.com/aristanetworks/ansible-avd/pull/1857)
- Feat(eos_cli_config_gen) - Support bgp additional-paths in router_bgp vrf address-families (https://github.com/aristanetworks/ansible-avd/pull/1854)
- Feat(eos_cli_config_gen) - Support bgp missing-policy under router bgp vrf address-families (https://github.com/aristanetworks/ansible-avd/pull/1897)
- Feat(eos_cli_config_gen) - enable global dot1x functionality (https://github.com/aristanetworks/ansible-avd/pull/1801)
- Feat(eos_designs) -  Structured configuration support for uplink and mlag interfaces (https://github.com/aristanetworks/ansible-avd/pull/1865)
- Feat(eos_designs) - Relax requirement of node-specific configuration (https://github.com/aristanetworks/ansible-avd/pull/1827)
- Feat(eos_designs) - Support for computing SNMP v3 engineid and hashes (https://github.com/aristanetworks/ansible-avd/pull/1868)
- Feat(eos_designs) - Support for short_esi - auto in port profiles & use of new eos_cli_config_gen data model (https://github.com/aristanetworks/ansible-avd/pull/1834)
- Feat(eos_designs) - Support raw_eos_cli key on core_interfaces (https://github.com/aristanetworks/ansible-avd/pull/1862)
- Feat(eos_designs) - add support for 7300X3 in default platforms (https://github.com/aristanetworks/ansible-avd/pull/1863)
- Feat(eos_designs,eos_cli_config_gen) - support 'switchport trunk native vlan tag' config (https://github.com/aristanetworks/ansible-avd/pull/1871)
- Feat(eos_snapshot) - Support for commands containing / character (https://github.com/aristanetworks/ansible-avd/pull/1838)
- Test(eos_cli_config_gen) - Add artifacts for router_bgp vrfs address_families peer_groups (https://github.com/aristanetworks/ansible-avd/pull/1858)

Bugfixes
--------

- Doc(eos_config_deploy_cvp) - fix the defaults values in README (https://github.com/aristanetworks/ansible-avd/pull/1902)
- Fix(eos_cli_config_gen) - VRF BGP neighbor allowas_in.enabled renders invalid config (https://github.com/aristanetworks/ansible-avd/pull/1891)
- Fix(eos_designs) - Correct pruning of vlans when no vlans are allowed (https://github.com/aristanetworks/ansible-avd/pull/1879)
- Fix(eos_designs) - Failure with OSPF underlay and mlag_peer_l3_vlan == mlag_peer_vlan (https://github.com/aristanetworks/ansible-avd/pull/1842)
- Fix(eos_designs) - Wrong passive interfaces rendered under OSPF process (https://github.com/aristanetworks/ansible-avd/pull/1893)
- Fix(eos_designs, eos_cli_config_gen) - Fix the AVD version print in virtual environments (https://github.com/aristanetworks/ansible-avd/pull/1876)
- Fix(eos_validate_state) - Follow alphabetical order on generated reports (https://github.com/aristanetworks/ansible-avd/pull/1867)

v3.5.0
======

Release Summary
---------------

Release 3.5.0 - See documentation on avd.sh for details.

Minor Changes
-------------

- Bump(requirements) - Relax ansible.netcommon requirements to ">=2.4.0,!=2.6.0" by @gmuloc (https://github.com/aristanetworks/ansible-avd/pull/1836)
- Doc - Fix typo in release-notes for v3.4.0 by @ClausHolbechArista (https://github.com/aristanetworks/ansible-avd/pull/1698)
- Doc - Improve documentation, fix typo by @danieltudares (https://github.com/aristanetworks/ansible-avd/pull/1749)
- Doc - Minor Corrections on Documentation by @JulioPDX (https://github.com/aristanetworks/ansible-avd/pull/1751)
- Doc - Network services data model in v4.0 mpls docs by @Shivani-chourasiya (https://github.com/aristanetworks/ansible-avd/pull/1794)
- Doc - Remove CI badge by @carlbuchmann (https://github.com/aristanetworks/ansible-avd/pull/1736)
- Doc - Update links to github documentation by @ClausHolbechArista (https://github.com/aristanetworks/ansible-avd/pull/1713)
- Doc(eos_cli_config_gen) - Improve documentation for router_general by @gmuloc (https://github.com/aristanetworks/ansible-avd/pull/1829)
- Doc(eos_designs) - add precisions regarding eos_designs and eos_cli_config_gen variables by @gmuloc (https://github.com/aristanetworks/ansible-avd/pull/1743)
- Feat(eos_cli_config_gen) - Add BGP listen-range to VRF by @ccsnw (https://github.com/aristanetworks/ansible-avd/pull/1779)
- Feat(eos_cli_config_gen) - Add BGP neighbor interfaces in VRF by @onurgashi (https://github.com/aristanetworks/ansible-avd/pull/1817)
- Feat(eos_cli_config_gen) - Add Tap Aggregation support by @ccsnw (https://github.com/aristanetworks/ansible-avd/pull/1737)
- Feat(eos_cli_config_gen) - Add eos_cli for loopback_interfaces by @UchihaItachiSama (https://github.com/aristanetworks/ansible-avd/pull/1707)
- Feat(eos_cli_config_gen) - Add eos_cli for loopback_interfaces by @UchihaItachiSama (https://github.com/aristanetworks/ansible-avd/pull/1707)
- Feat(eos_cli_config_gen) - Add management_api_models by @UchihaItachiSama (https://github.com/aristanetworks/ansible-avd/pull/1724)
- Feat(eos_cli_config_gen) - Add sflow interface disable default command by @xaviramon (https://github.com/aristanetworks/ansible-avd/pull/1823)
- Feat(eos_cli_config_gen) - Add support for authenticating only ntp servers by @UchihaItachiSama (https://github.com/aristanetworks/ansible-avd/pull/1810)
- Feat(eos_cli_config_gen) - Add support for multiple dot1x interface features by @mthiel117 (https://github.com/aristanetworks/ansible-avd/pull/1739)
- Feat(eos_cli_config_gen) - Added support for CVX client by @sugetha24 (https://github.com/aristanetworks/ansible-avd/pull/1682)
- Feat(eos_cli_config_gen) - Adding support for ssl profile for gnmi by @noredistribution (https://github.com/aristanetworks/ansible-avd/pull/1747)
- Feat(eos_cli_config_gen) - Aegis Traffic Policies on Interfaces by @emilarista (https://github.com/aristanetworks/ansible-avd/pull/1638)
- Feat(eos_cli_config_gen) - BGP VRF IPv4 RM support by @danieltudares (https://github.com/aristanetworks/ansible-avd/pull/1763)
- Feat(eos_cli_config_gen) - Extend listen_range support for BGP by @ccsnw (https://github.com/aristanetworks/ansible-avd/pull/1735)
- Feat(eos_cli_config_gen) - Extend logging format timestamp options by @ccsnw (https://github.com/aristanetworks/ansible-avd/pull/1709)
- Feat(eos_cli_config_gen) - Support Aboot password by @tgodaA (https://github.com/aristanetworks/ansible-avd/pull/1691)
- Feat(eos_cli_config_gen) - Support for multiple VARPv6 addresses by @onurgashi (https://github.com/aristanetworks/ansible-avd/pull/1761)
- Feat(eos_cli_config_gen) - Support interfaces snmp trap link-change by @tgodaA (https://github.com/aristanetworks/ansible-avd/pull/1703)
- Feat(eos_cli_config_gen) - Support platfom sand qos-mapping by @tgodaA (https://github.com/aristanetworks/ansible-avd/pull/1686)
- Feat(eos_cli_config_gen) - Support remove-private-as in router_bgp by @tgodaA (https://github.com/aristanetworks/ansible-avd/pull/1666)
- Feat(eos_cli_config_gen) - VRRP timer delay and IPv4 version options by @c-po (https://github.com/aristanetworks/ansible-avd/pull/1706)
- Feat(eos_cli_config_gen) - add PIM sparse-mode interfaces in doc by @gmuloc (https://github.com/aristanetworks/ansible-avd/pull/1848)
- Feat(eos_cli_config_gen) - add SNMPv3 hashed user passphrases support by @gmuloc (https://github.com/aristanetworks/ansible-avd/pull/1721)
- Feat(eos_cli_config_gen) - add VRRP support for object tracking by @ccsnw (https://github.com/aristanetworks/ansible-avd/pull/1637)
- Feat(eos_cli_config_gen) - dot1x-pae-mode by @mthiel117 (https://github.com/aristanetworks/ansible-avd/pull/1722)
- Feat(eos_cli_config_gen) - dot1x-reauthentication by @mthiel117 (https://github.com/aristanetworks/ansible-avd/pull/1700)
- Feat(eos_config_deploy_cvp) - support for !vault value in inventory file by @gmuloc (https://github.com/aristanetworks/ansible-avd/pull/1799)
- Feat(eos_designs) - Add ability to set mlag port-channel id by @ClausHolbechArista (https://github.com/aristanetworks/ansible-avd/pull/1789)
- Feat(eos_designs) - Add platform settings for 7368X4 by @gmuloc (https://github.com/aristanetworks/ansible-avd/pull/1690)
- Feat(eos_designs) - Auto short_esi support for connected_endpoints and l2leaf uplinks (#1609) by @jonxstill (https://github.com/aristanetworks/ansible-avd/pull/1738)
- Feat(eos_designs) - Custom name for underlay isis process by @emilarista (https://github.com/aristanetworks/ansible-avd/pull/1731)
- Feat(eos_designs) - EVPN VXLAN gateway feature by @xaviramon (https://github.com/aristanetworks/ansible-avd/pull/1601)
- Feat(eos_designs) - Enable RTC for EVPN-OVERLAY-CORE peer group by @onurgashi (https://github.com/aristanetworks/ansible-avd/pull/1775)
- Feat(eos_designs) - RFC5549 for MLAG iBGP in VRF by @onurgashi (https://github.com/aristanetworks/ansible-avd/pull/1818)
- Feat(eos_designs) - RFC5549 support for core_interfaces by @emilarista (https://github.com/aristanetworks/ansible-avd/pull/1741)
- Feat(eos_designs) - Shutdown underlay links if the peer device is not deployed by @perimore (https://github.com/aristanetworks/ansible-avd/pull/1745)
- Feat(eos_designs) - Support evpn hostflap detection expiry by @tgodaA (https://github.com/aristanetworks/ansible-avd/pull/1733)
- Feat(eos_designs) - Support for IPv6 in underlay with RFC5549 by @xaviramon (https://github.com/aristanetworks/ansible-avd/pull/1723)
- Feat(eos_designs) - Support for IPv6 overlay peerings with RFC5549 underlay by @xaviramon (https://github.com/aristanetworks/ansible-avd/pull/1719)
- Feat(eos_designs) - Support for Ipv6 network services by @onurgashi (https://github.com/aristanetworks/ansible-avd/pull/1760)
- Feat(eos_designs, eos_cli_config_gen) - Support default-services in management-api-http by @tgodaA (https://github.com/aristanetworks/ansible-avd/pull/1704)
- Feat(eos_designs, eos_cli_config_gen) - Support default-services in management-api-http by @tgodaA (https://github.com/aristanetworks/ansible-avd/pull/1704)
- Feat(plugins) - Updated convert_dicts filter for list values in dictionary by @Shivani-chourasiya (https://github.com/aristanetworks/ansible-avd/pull/1694)
- Feat(plugins) - Updated convert_dicts filter for list/string values in dictionary by @Shivani-chourasiya (https://github.com/aristanetworks/ansible-avd/pull/1740)

Bugfixes
--------

- Fix(eos_cli_config_gen) - Adjust the address-family evpn host-flap detection by @tgodaA (https://github.com/aristanetworks/ansible-avd/pull/1728)
- Fix(eos_cli_config_gen) - Documentation template for IPv6 on port-channels by @ClausHolbechArista (https://github.com/aristanetworks/ansible-avd/pull/1715)
- Fix(eos_cli_config_gen) - Render error-correction encoding on port-channel members by @ClausHolbechArista (https://github.com/aristanetworks/ansible-avd/pull/1800)
- Fix(eos_designs) - Error in eos_designs_facts when dot in hostname by @ClausHolbechArista (https://github.com/aristanetworks/ansible-avd/pull/1816)
- Fix(eos_designs) - Fix IPv6 static routes tenants by @onurgashi (https://github.com/aristanetworks/ansible-avd/pull/1778)
- Fix(eos_designs) - ipv6_underlay should not apply for l2 switches by @ClausHolbechArista (https://github.com/aristanetworks/ansible-avd/pull/1812)
- Fix(plugins) - convert_dicts resolve corner case with dictionary with invalid value by @carlbuchmann (https://github.com/aristanetworks/ansible-avd/pull/1777)

New Modules
-----------

- arista.avd.eos_designs_facts - Set eos_designs facts
