.. _platform_options:

****************
Platform Options
****************

Some Ansible Network platforms support multiple connection types, privilege escalation (``enable`` mode), or other options. The pages in this section offer standardized guides to understanding available options on each network platform. We welcome contributions from community-maintained platforms to this section.

.. toctree::
   :maxdepth: 2
   :caption: Platform Options

   platform_cnos
   platform_dellos6
   platform_dellos9
   platform_dellos10
   platform_enos
   platform_eos
   platform_exos
   platform_ios
   platform_ironware
   platform_junos
   platform_netvisor
   platform_nos
   platform_nxos
   platform_routeros
   platform_slxos
   platform_voss
   platform_netconf_enabled

.. _settings_by_platform:

Settings by Platform
================================

+-------------------+-------------------------+--------------+---------+---------+---------+
|..                 |                         | ``ansible_connection:`` settings available |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Network OS        | ``ansible_network_os:`` | network_cli | netconf | httpapi | local    |
+===================+=========================+=============+=========+=========+==========+
| Arista EOS*       | ``eos``                 | ✓           |         | ✓       | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Cisco ASA         | ``asa``                 | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Cisco IOS*        | ``ios``                 | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Cisco IOS XR*     | ``iosxr``               | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Cisco NX-OS*      | ``nxos``                | ✓           |         | ✓       | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Dell OS6          | ``dellos6``             | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Dell OS9          | ``dellos9``             | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Dell OS10         | ``dellos10``            | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Extreme EXOS      | ``exos``                | ✓           |         |         |          |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Extreme IronWare  | ``ironware``            | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Extreme NOS       | ``nos``                 | ✓           |         |         |          |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Extreme SLX-OS    | ``slxos``               | ✓           |         |         |          |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Extreme VOSS      | ``voss``                | ✓           |         |         |          |
+-------------------+-------------------------+-------------+---------+---------+----------+
| F5 BIG-IP         |                         |             |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| F5 BIG-IQ         |                         |             |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Junos OS*         | ``junos``               | ✓           | ✓       |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Lenovo CNOS       | ``cnos``                | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Lenovo ENOS       | ``enos``                | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| MikroTik RouterOS | ``routeros``            | ✓           |         |         |          |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Nokia SR OS       | ``sros``                | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| Pluribus Netvisor | ``netvisor``            | ✓           |         |         |          |
+-------------------+-------------------------+-------------+---------+---------+----------+
| VyOS*             | ``vyos``                | ✓           |         |         | ✓        |
+-------------------+-------------------------+-------------+---------+---------+----------+
| OS that supports  | ``<network-os>``        |             | ✓       |         | ✓        |
| Netconf*          |                         |             |         |         |          |
+-------------------+-------------------------+-------------+---------+---------+----------+

`*` Maintained by Ansible Network Team
