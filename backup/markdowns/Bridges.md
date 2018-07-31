# Bridges
## ifquery bridge
```

error: cannot find interfaces: bridge

```
```

nohup: failed to run command ‘ifquery’: No such file or directory

```
## sudo bridge fdb show
```

02:42:0d:8c:08:22 dev docker0 master docker0 permanent

```
```

02:42:0d:8c:08:22 dev docker0 master docker0 permanent

```
## net show bridge macs
```


VLAN      Master    Interface    MAC                  TunnelDest  State      Flags    LastSeen
--------  --------  -----------  -----------------  ------------  ---------  -------  ----------
untagged  docker0   docker0      02:42:0d:8c:08:22                permanent           01:39:34

```
```

The following commands contain keyword(s) 'show', 'bridge', 'macs'

    net show bridge macs <ip> [json]
    net show bridge macs <mac> [json]
    net show bridge macs [json]
    net show bridge macs dynamic [json]
    net show bridge macs permanent [json]
    net show bridge macs vlan <number> [json]


```
## cat /etc/network/interfaces
```

auto lo
iface lo inet loopback
    address 10.0.0.41/32
    address fd00::41/128

auto eth0
iface eth0 inet static
    address 10.255.0.1
    netmask 255.255.0.0
    gateway 10.255.0.3
auto eth1
iface eth1 inet static
    address 192.168.0.254
    netmask 255.255.0.0

auto eth2
iface eth2

auto eth3
iface eth3

```
```

Usage: cat [OPTION]... [FILE]...
Concatenate FILE(s), or standard input, to standard output.

  -A, --show-all           equivalent to -vET
  -b, --number-nonblank    number nonempty output lines, overrides -n
  -e                       equivalent to -vE
  -E, --show-ends          display $ at end of each line
  -n, --number             number all output lines
  -s, --squeeze-blank      suppress repeated empty output lines
  -t                       equivalent to -vT
  -T, --show-tabs          display TAB characters as ^I
  -u                       (ignored)
  -v, --show-nonprinting   use ^ and M- notation, except for LFD and TAB
      --help     display this help and exit
      --version  output version information and exit

With no FILE, or when FILE is -, read standard input.

Examples:
  cat f - g  Output f's contents, then standard input, then g's contents.
  cat        Copy standard input to standard output.

GNU coreutils online help: <http://www.gnu.org/software/coreutils/>
Full documentation at: <http://www.gnu.org/software/coreutils/cat>
or available locally via: info '(coreutils) cat invocation'

auto lo
iface lo inet loopback
    address 10.0.0.41/32
    address fd00::41/128

auto eth0
iface eth0 inet static
    address 10.255.0.1
    netmask 255.255.0.0
    gateway 10.255.0.3
auto eth1
iface eth1 inet static
    address 192.168.0.254
    netmask 255.255.0.0

auto eth2
iface eth2

auto eth3
iface eth3

```
## ip link show
```

1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN mode DEFAULT group default 
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:00 brd ff:ff:ff:ff:ff:ff
3: eth1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:01 brd ff:ff:ff:ff:ff:ff
4: eth2: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:02 brd ff:ff:ff:ff:ff:ff
5: eth3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:03 brd ff:ff:ff:ff:ff:ff
6: docker0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc noqueue state DOWN mode DEFAULT group default 
    link/ether 02:42:0d:8c:08:22 brd ff:ff:ff:ff:ff:ff

```
```

Device "--help" does not exist.

1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN mode DEFAULT group default 
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:00 brd ff:ff:ff:ff:ff:ff
3: eth1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:01 brd ff:ff:ff:ff:ff:ff
4: eth2: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:02 brd ff:ff:ff:ff:ff:ff
5: eth3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:03 brd ff:ff:ff:ff:ff:ff
6: docker0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc noqueue state DOWN mode DEFAULT group default 
    link/ether 02:42:0d:8c:08:22 brd ff:ff:ff:ff:ff:ff

```
## net show configuration files
```

/etc/network/interfaces
=======================
auto lo
iface lo inet loopback
    address 10.0.0.41/32
    address fd00::41/128

auto eth0
iface eth0 inet static
    address 10.255.0.1
    netmask 255.255.0.0
    gateway 10.255.0.3
auto eth1
iface eth1 inet static
    address 192.168.0.254
    netmask 255.255.0.0

auto eth2
iface eth2

auto eth3
iface eth3


/etc/hostname
=============
oob-mgmt-server


/etc/hosts
==========
127.0.0.1	localhost
::1		localhost ip6-localhost ip6-loopback
ff02::1		ip6-allnodes
ff02::2		ip6-allrouters

127.0.1.1	cumulus
127.0.1.1 redis_master
192.168.0.254 oob-mgmt-server
192.168.0.14 leaf04
192.168.0.12 leaf02
192.168.0.13 leaf03
192.168.0.11 leaf01
192.168.0.22 spine02
192.168.0.21 spine01
192.168.0.31 server01
192.168.0.33 server03
192.168.0.32 server02
192.168.0.34 server04


/etc/dhcp/dhclient-exit-hooks.d/dhcp-sethostname
================================================
# This script sets the machine hostname to the hostname sent from the DHCP server.
# If you want to enable this script, change SETHOSTNAME to "yes"
# Copyright 2013, 2015, 2017, Cumulus Networks, Inc.  All rights reserved.

SETHOSTNAME="yes"

if [ $SETHOSTNAME = "yes" ] && [ ! -z $new_host_name ]
then
    hostname $new_host_name
    sed --in-place -e "/127\.0\.1\.1/s/^.*$/127.0.1.1  $new_host_name/" /etc/hosts
fi


/etc/default/isc-dhcp-relay
===========================
# Defaults for isc-dhcp-relay initscript
# sourced by /etc/init.d/isc-dhcp-relay
# installed at /etc/default/isc-dhcp-relay by the maintainer scripts

#
# This is a POSIX shell fragment
#

# What servers should the DHCP relay forward requests to?
SERVERS=""

# On what interfaces should the DHCP relay (dhrelay) serve DHCP requests?
# Always include the interface towards the DHCP server.
# This variable requires a -i for each interface configured above.
# This will be used in the actual dhcrelay command
# For example, "-i eth0 -i eth1"
INTF_CMD=""

# Additional options that are passed to the DHCP relay daemon?
OPTIONS=""


/etc/default/isc-dhcp-relay6
============================
# Defaults for isc-dhcp-relay6 initscript
# sourced by /etc/init.d/isc-dhcp-relay6
# installed at /etc/default/isc-dhcp-relay6 by the maintainer scripts

#
# This is a POSIX shell fragment
#

# Specify upstream and downstream interfaces
# For example, "-u eth0 -l swp1"
INTF_CMD=""

# Additional options that are passed to the DHCP relay daemon?
OPTIONS=""


/etc/default/isc-dhcp-server
============================
# Defaults for isc-dhcp-server initscript
# sourced by /etc/init.d/isc-dhcp-server
# installed at /etc/default/isc-dhcp-server by the maintainer scripts

#
# This is a POSIX shell fragment
#

# Path to dhcpd's config file (default: /etc/dhcp/dhcpd.conf).
#DHCPD_CONF="-cf /etc/dhcp/dhcpd.conf"

# Path to dhcpd's PID file (default: /var/run/dhcpd.pid).
#DHCPD_PID="-pf /var/run/dhcpd.pid"

# Additional options to start dhcpd with.
#	Don't use options -cf or -pf here; use DHCPD_CONF/ DHCPD_PID instead
#OPTIONS=""

# On what interfaces should the DHCP server (dhcpd) serve DHCP requests?
#	Separate multiple interfaces with spaces, e.g. "eth0 eth1".
INTERFACES=""


/etc/default/isc-dhcp-server6
=============================
# Defaults for isc-dhcp-server6 initscript
# sourced by /etc/init.d/isc-dhcp-server
# installed at /etc/default/isc-dhcp-server6 by the maintainer scripts

#
# This is a POSIX shell fragment
#

# Path to dhcpd's config file (default: /etc/dhcp/dhcpd6.conf).
#DHCPD_CONF="-cf /etc/dhcp/dhcpd6.conf"

# Path to dhcpd's PID file (default: /var/run/dhcpd6.pid).
#DHCPD_PID="-pf /var/run/dhcpd6.pid"

# Additional options to start dhcpd with.
#	Don't use options -cf or -pf here; use DHCPD_CONF/ DHCPD_PID instead
#OPTIONS=""

# On what interfaces should the DHCP server (dhcpd) serve DHCP requests?
#	Separate multiple interfaces with spaces, e.g. "eth0 eth1".
INTERFACES=""


/etc/cumulus/ports.conf
=======================
# ports.conf --
#
#   configure port speed, aggregation, and subdivision.
#
#   The ports in Cumulus VX are not configurable from here.
#

/etc/frr/daemons
===================
zebra=yes
bgpd=yes
ospfd=no
ospf6d=no
ripd=no
ripngd=no
isisd=no
pimd=no
ldpd=no
nhrpd=no
eigrpd=no
babeld=no


/etc/frr/frr.conf
=======================
frr version 3.2+cl3u4
frr defaults datacenter
hostname oob-mgmt-server
username cumulus nopassword
!
service integrated-vtysh-config
!
log syslog informational
!
interface eth2
 ipv6 nd ra-interval 10
 no ipv6 nd suppress-ra
!
interface eth3
 ipv6 nd ra-interval 10
 no ipv6 nd suppress-ra
!
router bgp 65041
 bgp router-id 10.0.0.41
 coalesce-time 1000
 bgp bestpath as-path multipath-relax
 neighbor eth2 interface remote-as external
 neighbor eth3 interface remote-as external
 !
 address-family ipv4 unicast
  network 10.0.0.41/32
  network 10.0.2.0/24
 exit-address-family
 !
 address-family ipv6 unicast
  network fd00::41/128
  neighbor eth2 activate
  neighbor eth3 activate
 exit-address-family
!
line vty
!


/etc/vxsnd.conf
===============
[common]
# Log level is one of DEBUG, INFO, WARNING, ERROR, CRITICAL
#loglevel = INFO

# Destination for log message.  Can be a file name, 'stdout', or 'syslog'
#logdest = syslog

# log file size in bytes. Used when logdest is a file
#logfilesize = 512000

# maximum number of log files stored on disk. Used when logdest is a file
#logbackupcount = 14

# The file to write the pid.
#pidfile = /var/run/vxsnd.pid

# The file name for the unix domain socket used for mgmt.
#udsfile = /var/run/vxsnd.sock

# UDP port for vxfld control messages
#vxfld_port = 10001

# This is the address to which registration daemons send control messages for
# registration and/or BUM packets for replication
#svcnode_ip = 0.0.0.0

# Holdtime (in seconds) for soft state. It is used when sending a
# register msg to peers in response to learning a <vni, addr> from a
# VXLAN data pkt
#holdtime = 90

# Local IP address to bind to for receiving inter-vxsnd control traffic
#src_ip = 0.0.0.0

[vxsnd]
# Space separated list of IP addresses of vxsnd to share state with
#svcnode_peers =

# When set to true, the service node will listen for vxlan data traffic
# Note: Use 1, yes, true, or on, for True and 0, no, false, or off,
# for False
#enable_vxlan_listen = true

# When set to true, the svcnode_ip will be installed on the loopback
# interface, and it will be withdrawn when the vxsnd is no longer in
# service.  If set to true, the svcnode_ip configuration
# variable must be defined.
# Note: Use 1, yes, true, or on, for True and 0, no, false, or off,
# for False
#install_svcnode_ip = false

# Seconds to wait before checking the database to age out stale entries
#age_check = 90

/etc/hostapd.conf
=======================
#### Auto-generated config file: do not edit. ####
eap_server=0
ieee8021x=1
driver=wired
interfaces=
mab_interfaces=
parking_vlan_interfaces=
parking_vlan_id=
mab_activation_delay=30
eap_reauth_period=0
ctrl_interface=/var/run/hostapd
nas_identifier=localhost
auth_server_addr=
auth_server_port=1812
auth_server_shared_secret=
acct_server_addr=
acct_server_port=1813
acct_server_shared_secret=


/etc/ntp.conf
=============
# /etc/ntp.conf, configuration for ntpd; see ntp.conf(5) for help

driftfile /var/lib/ntp/ntp.drift


# Enable this if you want statistics to be logged.
#statsdir /var/log/ntpstats/

statistics loopstats peerstats clockstats
filegen loopstats file loopstats type day enable
filegen peerstats file peerstats type day enable
filegen clockstats file clockstats type day enable


# You do need to talk to an NTP server or two (or three).
#server ntp.your-provider.example

# pool.ntp.org maps to about 1000 low-stratum NTP servers.  Your server will
# pick a different set every time it starts up.  Please consider joining the
# pool: <http://www.pool.ntp.org/join.html>
server 0.cumulusnetworks.pool.ntp.org iburst
server 1.cumulusnetworks.pool.ntp.org iburst
server 2.cumulusnetworks.pool.ntp.org iburst
server 3.cumulusnetworks.pool.ntp.org iburst


# Access control configuration; see /usr/share/doc/ntp-doc/html/accopt.html for
# details.  The web page <http://support.ntp.org/bin/view/Support/AccessRestrictions>
# might also be helpful.
#
# Note that "restrict" applies to both servers and clients, so a configuration
# that might be intended to block requests from certain clients could also end
# up blocking replies from your own upstream servers.

# By default, exchange time with everybody, but don't allow configuration.
restrict -4 default kod notrap nomodify nopeer noquery
restrict -6 default kod notrap nomodify nopeer noquery

# Local users may interrogate the ntp server more closely.
restrict 127.0.0.1
restrict ::1

# Clients from this (example!) subnet have unlimited access, but only if
# cryptographically authenticated.
#restrict 192.168.123.0 mask 255.255.255.0 notrust


# If you want to provide time to your local subnet, change the next line.
# (Again, the address is an example only.)
#broadcast 192.168.123.255

# If you want to listen to time broadcasts on your local subnet, de-comment the
# next lines.  Please do this only if you trust everybody on the network!
#disable auth
#broadcastclient

# Specify interfaces, don't listen on switch ports
interface listen eth0


/etc/timezone
=============
Etc/UTC

/etc/rsyslog.d/11-remotesyslog.conf
===================================
# This file was automatically generated by NCLU.

/etc/resolv.conf
================
nameserver 8.8.8.8

/etc/snmp/snmpd.conf
=======================
#### Auto-generated config file: do not edit. ####
agentAddress 127.0.0.1
agentxperms 777 777 snmp snmp
agentxsocket /var/agentx/master
createUser _snmptrapusernameX
iquerySecName _snmptrapusernameX
master agentx
monitor -r 60 -o laNames -o laErrMessage "laTable" laErrorFlag != 0
pass -p 10 1.3.6.1.2.1.1.1 /usr/share/snmp/sysDescr_pass.py
pass_persist 1.2.840.10006.300.43 /usr/share/snmp/ieee8023_lag_pp.py
pass_persist 1.3.6.1.2.1.17 /usr/share/snmp/bridge_pp.py
pass_persist 1.3.6.1.2.1.31.1.1.1.18 /usr/share/snmp/snmpifAlias_pp.py
pass_persist 1.3.6.1.2.1.47 /usr/share/snmp/entity_pp.py
pass_persist 1.3.6.1.2.1.99 /usr/share/snmp/entity_sensor_pp.py
pass_persist 1.3.6.1.4.1.40310.1 /usr/share/snmp/resq_pp.py
pass_persist 1.3.6.1.4.1.40310.2 /usr/share/snmp/cl_drop_cntrs_pp.py
rouser _snmptrapusernameX
sysObjectID 1.3.6.1.4.1.40310
sysServices 72


```
```

The following commands contain keyword(s) 'show', 'configuration', 'files'

    net show configuration files


```
## net show bridge vlan
```


Interface    VLAN    Flags
-----------  ------  -------


```
```

The following commands contain keyword(s) 'show', 'bridge', 'vlan'

    net show bridge macs vlan <number> [json]
    net show bridge vlan [<number>] [json]


```
## netq show vlan
```


Matching vlan records:
Hostname          VLANs                     SVIs                      Last Changed
----------------- ------------------------- ------------------------- ----------------
server01          1                         -                         1h:38m:11s
server02          1                         -                         1h:38m:9s
server03          1                         -                         1h:38m:13s
server04          1                         -                         1h:38m:13s

```
```

The following commands contain keyword(s) 'show', 'vlan'

    netq <hostname> show macs egress-port <egress-port> [<mac>] vlan <1-4096> [origin] [json]
    netq <hostname> show macs egress-port <egress-port> [<mac>] vlan <1-4096> [origin] around <text-time> [json]
    netq <hostname> show macs egress-port <egress-port> [<mac>] vlan <1-4096> [origin] changes [json]
    netq <hostname> show macs egress-port <egress-port> [<mac>] vlan <1-4096> [origin] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) [count] [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) around <text-time> [count] [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) changes [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) state <remote-interface-state> [count] [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) state <remote-interface-state> around <text-time> [count] [json]
    netq [<hostname>] show macs [<mac>] vlan <1-4096> [origin] [json]
    netq [<hostname>] show macs [<mac>] vlan <1-4096> [origin] around <text-time> [json]
    netq [<hostname>] show macs [<mac>] vlan <1-4096> [origin] changes [json]
    netq [<hostname>] show macs [<mac>] vlan <1-4096> [origin] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show macs [<mac>] vlan <1-4096> around <text-time> count [json]
    netq [<hostname>] show macs [<mac>] vlan <1-4096> count [json]
    netq [<hostname>] show vlan [<1-4096>] [json]
    netq [<hostname>] show vlan [<1-4096>] around <text-time> [json]
    netq [<hostname>] show vlan [<1-4096>] changes [json]
    netq [<hostname>] show vlan [<1-4096>] changes between <text-time> and <text-endtime> [json]


Unable to find command netq show vlan --help


Matching vlan records:
Hostname          VLANs                     SVIs                      Last Changed
----------------- ------------------------- ------------------------- ----------------
server01          1                         -                         1h:38m:11s
server02          1                         -                         1h:38m:9s
server03          1                         -                         1h:38m:13s
server04          1                         -                         1h:38m:13s

```
## netq check vlan
```

[92mChecked Nodes: 11, Checked Links: 110, Failed Nodes: 0, Failed Links: 0[0m
No VLAN or PVID Mismatch found

```
```

The following commands contain keyword(s) 'check', 'vlan'

    netq check vlan [unverified] [json]
    netq check vlan [unverified] around <text-time> [json]


Unable to find command netq check vlan --help

[92mChecked Nodes: 11, Checked Links: 110, Failed Nodes: 0, Failed Links: 0[0m
No VLAN or PVID Mismatch found

```
## netq show ip neighbors
```


Matching neighbor records:
IP Address                Hostname          Interface                 Mac Address              VRF              Remote Last Changed
------------------------- ----------------- ------------------------- ------------------------ ---------------- ------ ----------------
10.244.135.137            server04          calia1512473e0b           9e:80:99:ca:0f:2f        default          no     1h:36m:33s
10.244.135.138            server04          cali24ab13fd7c6           7a:cc:3d:57:8d:0a        default          no     1h:36m:33s
10.244.135.139            server04          calif3852dd8310           c2:30:11:8c:57:55        default          no     1h:36m:32s
10.244.188.6              server01          cali8ec1d1ccd89           1e:c4:b2:06:90:d9        default          no     1h:36m:19s
10.244.188.7              server01          cali41761d66072           6e:14:3e:68:0d:a1        default          no     1h:36m:11s
10.244.40.204             server03          calid4504ded79f           e6:42:66:7b:56:23        default          no     1h:36m:37s
10.244.40.205             server03          cali6f7cd6a5112           f6:55:91:34:96:4f        default          no     1h:36m:37s
10.244.40.206             server03          calic8efae22f6c           d2:ef:77:8c:bd:b5        default          no     1h:36m:37s
10.244.40.207             server03          cali76e21be405c           4a:ab:32:b2:74:d6        default          no     1h:36m:36s
10.244.6.10               server02          cali1332f51f81b           42:fc:98:56:aa:c8        default          no     1h:36m:44s
10.244.6.11               server02          cali6bb7f391314           26:1e:f7:cd:90:77        default          no     1h:36m:43s
10.244.6.9                server02          calic0bf60df561           5a:ba:e7:1a:d4:1c        default          no     1h:36m:45s
10.255.0.3                oob-mgmt-server   eth0                      2c:c2:60:ff:00:4d        default          no     2d:19h:7m:8s
169.254.0.1               leaf01            swp1                      44:38:39:00:08:01        default          no     2d:19h:2m:30s
169.254.0.1               leaf01            swp2                      44:38:39:00:09:01        default          no     2d:19h:2m:29s
169.254.0.1               leaf01            swp44                     44:38:39:00:01:02        default          no     2d:19h:3m:44s
169.254.0.1               leaf01            swp51                     44:38:39:00:06:01        default          no     2d:19h:3m:34s
169.254.0.1               leaf01            swp52                     44:38:39:00:07:01        default          no     2d:19h:3m:34s
169.254.0.1               leaf02            swp1                      44:38:39:00:08:02        default          no     2d:19h:2m:30s
169.254.0.1               leaf02            swp2                      44:38:39:00:09:02        default          no     2d:19h:2m:28s
169.254.0.1               leaf02            swp44                     44:38:39:00:01:03        default          no     2d:19h:3m:53s
169.254.0.1               leaf02            swp51                     44:38:39:00:06:02        default          no     2d:19h:3m:33s
169.254.0.1               leaf02            swp52                     44:38:39:00:07:02        default          no     2d:19h:3m:33s
169.254.0.1               leaf03            swp1                      44:38:39:00:0a:01        default          no     2d:19h:2m:29s
169.254.0.1               leaf03            swp2                      44:38:39:00:0b:01        default          no     2d:19h:2m:28s
169.254.0.1               leaf03            swp51                     44:38:39:00:06:03        default          no     2d:19h:3m:33s
169.254.0.1               leaf03            swp52                     44:38:39:00:07:03        default          no     2d:19h:3m:33s
169.254.0.1               leaf04            swp1                      44:38:39:00:0a:02        default          no     2d:19h:2m:29s
169.254.0.1               leaf04            swp2                      44:38:39:00:0b:02        default          no     2d:19h:2m:29s
169.254.0.1               leaf04            swp51                     44:38:39:00:06:04        default          no     2d:19h:3m:33s
169.254.0.1               leaf04            swp52                     44:38:39:00:07:04        default          no     2d:19h:3m:33s
169.254.0.1               oob-mgmt-server   eth2                      44:38:39:00:02:07        default          no     2d:19h:3m:51s
169.254.0.1               oob-mgmt-server   eth3                      44:38:39:00:03:07        default          no     2d:19h:3m:54s
169.254.0.1               server01          eth1                      44:38:39:00:02:05        default          no     2d:18h:57m:41s
169.254.0.1               server01          eth2                      44:38:39:00:03:05        default          no     2d:18h:57m:41s
169.254.0.1               server02          eth1                      44:38:39:00:02:06        default          no     2d:18h:57m:40s
169.254.0.1               server02          eth2                      44:38:39:00:03:06        default          no     2d:18h:57m:40s
169.254.0.1               server03          eth1                      44:38:39:00:04:05        default          no     2d:18h:57m:40s
169.254.0.1               server03          eth2                      44:38:39:00:05:05        default          no     2d:18h:57m:40s
169.254.0.1               server04          eth1                      44:38:39:00:04:06        default          no     2d:18h:57m:40s
169.254.0.1               server04          eth2                      44:38:39:00:05:06        default          no     2d:18h:57m:40s
169.254.0.1               spine01           swp1                      44:38:39:00:02:01        default          no     2d:19h:3m:27s
169.254.0.1               spine01           swp2                      44:38:39:00:03:01        default          no     2d:19h:3m:27s
169.254.0.1               spine01           swp3                      44:38:39:00:04:01        default          no     2d:19h:3m:28s
169.254.0.1               spine01           swp4                      44:38:39:00:05:01        default          no     2d:19h:3m:28s
169.254.0.1               spine02           swp1                      44:38:39:00:02:02        default          no     2d:19h:3m:27s
169.254.0.1               spine02           swp2                      44:38:39:00:03:02        default          no     2d:19h:3m:27s
169.254.0.1               spine02           swp3                      44:38:39:00:04:02        default          no     2d:19h:3m:27s
169.254.0.1               spine02           swp4                      44:38:39:00:05:02        default          no     2d:19h:3m:27s
192.168.0.11              oob-mgmt-server   eth1                      44:38:39:00:02:00        default          no     2d:19h:5m:48s
192.168.0.12              oob-mgmt-server   eth1                      44:38:39:00:03:00        default          no     2d:19h:5m:34s
192.168.0.13              oob-mgmt-server   eth1                      44:38:39:00:04:00        default          no     2d:19h:5m:34s
192.168.0.14              oob-mgmt-server   eth1                      44:38:39:00:05:00        default          no     2d:19h:7m:8s
192.168.0.21              oob-mgmt-server   eth1                      44:38:39:00:06:00        default          no     2d:19h:5m:36s
192.168.0.22              oob-mgmt-server   eth1                      44:38:39:00:07:00        default          no     2d:19h:5m:34s
192.168.0.254             leaf01            eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:9s
192.168.0.254             leaf02            eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:9s
192.168.0.254             leaf03            eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:8s
192.168.0.254             leaf04            eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:7s
192.168.0.254             server01          eth0                      44:38:39:00:01:01        default          no     2d:18h:57m:41s
192.168.0.254             server02          eth0                      44:38:39:00:01:01        default          no     2d:18h:57m:40s
192.168.0.254             server03          eth0                      44:38:39:00:01:01        default          no     2d:18h:57m:40s
192.168.0.254             server04          eth0                      44:38:39:00:01:01        default          no     2d:18h:57m:40s
192.168.0.254             spine01           eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:9s
192.168.0.254             spine02           eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:9s
192.168.0.31              oob-mgmt-server   eth1                      44:38:39:00:08:00        default          no     2d:19h:7m:8s
192.168.0.32              oob-mgmt-server   eth1                      44:38:39:00:09:00        default          no     2d:19h:7m:8s
192.168.0.33              oob-mgmt-server   eth1                      44:38:39:00:0a:00        default          no     2d:19h:7m:8s
192.168.0.34              oob-mgmt-server   eth1                      44:38:39:00:0b:00        default          no     2d:19h:7m:8s

```
```

The following commands contain keyword(s) 'show', 'ip', 'neighbors'

    netq [<hostname>] show ip neighbors [<remote-interface>] <ipv4> [<mac>] [count] [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] <ipv4> [<mac>] around <text-time> [count] [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] <ipv4> [<mac>] changes [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] <ipv4> [<mac>] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] <ipv4> vrf <vrf> [<mac>] [count] [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] <ipv4> vrf <vrf> [<mac>] around <text-time> [count] [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] <ipv4> vrf <vrf> [<mac>] changes [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] <ipv4> vrf <vrf> [<mac>] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] [<mac>] [count] [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] [<mac>] around <text-time> [count] [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] [<mac>] changes [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] [<mac>] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] vrf <vrf> [<mac>] [count] [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] vrf <vrf> [<mac>] around <text-time> [count] [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] vrf <vrf> [<mac>] changes [json]
    netq [<hostname>] show ip neighbors [<remote-interface>] vrf <vrf> [<mac>] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] <ipv6> [<mac>] [count] [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] <ipv6> [<mac>] around <text-time> [count] [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] <ipv6> [<mac>] changes [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] <ipv6> [<mac>] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] <ipv6> vrf <vrf> [<mac>] [count] [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] <ipv6> vrf <vrf> [<mac>] around <text-time> [count] [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] <ipv6> vrf <vrf> [<mac>] changes [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] <ipv6> vrf <vrf> [<mac>] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] [<mac>] [count] [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] [<mac>] around <text-time> [count] [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] [<mac>] changes [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] [<mac>] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] vrf <vrf> [<mac>] [count] [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] vrf <vrf> [<mac>] around <text-time> [count] [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] vrf <vrf> [<mac>] changes [json]
    netq [<hostname>] show ipv6 neighbors [<remote-interface>] vrf <vrf> [<mac>] changes between <text-time> and <text-endtime> [json]


Unable to find command netq show ip neighbors --help


Matching neighbor records:
IP Address                Hostname          Interface                 Mac Address              VRF              Remote Last Changed
------------------------- ----------------- ------------------------- ------------------------ ---------------- ------ ----------------
10.244.135.137            server04          calia1512473e0b           9e:80:99:ca:0f:2f        default          no     1h:36m:33s
10.244.135.138            server04          cali24ab13fd7c6           7a:cc:3d:57:8d:0a        default          no     1h:36m:33s
10.244.135.139            server04          calif3852dd8310           c2:30:11:8c:57:55        default          no     1h:36m:32s
10.244.188.6              server01          cali8ec1d1ccd89           1e:c4:b2:06:90:d9        default          no     1h:36m:19s
10.244.188.7              server01          cali41761d66072           6e:14:3e:68:0d:a1        default          no     1h:36m:11s
10.244.40.204             server03          calid4504ded79f           e6:42:66:7b:56:23        default          no     1h:36m:37s
10.244.40.205             server03          cali6f7cd6a5112           f6:55:91:34:96:4f        default          no     1h:36m:37s
10.244.40.206             server03          calic8efae22f6c           d2:ef:77:8c:bd:b5        default          no     1h:36m:37s
10.244.40.207             server03          cali76e21be405c           4a:ab:32:b2:74:d6        default          no     1h:36m:36s
10.244.6.10               server02          cali1332f51f81b           42:fc:98:56:aa:c8        default          no     1h:36m:44s
10.244.6.11               server02          cali6bb7f391314           26:1e:f7:cd:90:77        default          no     1h:36m:43s
10.244.6.9                server02          calic0bf60df561           5a:ba:e7:1a:d4:1c        default          no     1h:36m:45s
10.255.0.3                oob-mgmt-server   eth0                      2c:c2:60:ff:00:4d        default          no     2d:19h:7m:8s
169.254.0.1               leaf01            swp1                      44:38:39:00:08:01        default          no     2d:19h:2m:30s
169.254.0.1               leaf01            swp2                      44:38:39:00:09:01        default          no     2d:19h:2m:29s
169.254.0.1               leaf01            swp44                     44:38:39:00:01:02        default          no     2d:19h:3m:44s
169.254.0.1               leaf01            swp51                     44:38:39:00:06:01        default          no     2d:19h:3m:34s
169.254.0.1               leaf01            swp52                     44:38:39:00:07:01        default          no     2d:19h:3m:34s
169.254.0.1               leaf02            swp1                      44:38:39:00:08:02        default          no     2d:19h:2m:30s
169.254.0.1               leaf02            swp2                      44:38:39:00:09:02        default          no     2d:19h:2m:28s
169.254.0.1               leaf02            swp44                     44:38:39:00:01:03        default          no     2d:19h:3m:53s
169.254.0.1               leaf02            swp51                     44:38:39:00:06:02        default          no     2d:19h:3m:33s
169.254.0.1               leaf02            swp52                     44:38:39:00:07:02        default          no     2d:19h:3m:33s
169.254.0.1               leaf03            swp1                      44:38:39:00:0a:01        default          no     2d:19h:2m:29s
169.254.0.1               leaf03            swp2                      44:38:39:00:0b:01        default          no     2d:19h:2m:28s
169.254.0.1               leaf03            swp51                     44:38:39:00:06:03        default          no     2d:19h:3m:33s
169.254.0.1               leaf03            swp52                     44:38:39:00:07:03        default          no     2d:19h:3m:33s
169.254.0.1               leaf04            swp1                      44:38:39:00:0a:02        default          no     2d:19h:2m:29s
169.254.0.1               leaf04            swp2                      44:38:39:00:0b:02        default          no     2d:19h:2m:29s
169.254.0.1               leaf04            swp51                     44:38:39:00:06:04        default          no     2d:19h:3m:33s
169.254.0.1               leaf04            swp52                     44:38:39:00:07:04        default          no     2d:19h:3m:33s
169.254.0.1               oob-mgmt-server   eth2                      44:38:39:00:02:07        default          no     2d:19h:3m:51s
169.254.0.1               oob-mgmt-server   eth3                      44:38:39:00:03:07        default          no     2d:19h:3m:54s
169.254.0.1               server01          eth1                      44:38:39:00:02:05        default          no     2d:18h:57m:41s
169.254.0.1               server01          eth2                      44:38:39:00:03:05        default          no     2d:18h:57m:41s
169.254.0.1               server02          eth1                      44:38:39:00:02:06        default          no     2d:18h:57m:40s
169.254.0.1               server02          eth2                      44:38:39:00:03:06        default          no     2d:18h:57m:40s
169.254.0.1               server03          eth1                      44:38:39:00:04:05        default          no     2d:18h:57m:40s
169.254.0.1               server03          eth2                      44:38:39:00:05:05        default          no     2d:18h:57m:40s
169.254.0.1               server04          eth1                      44:38:39:00:04:06        default          no     2d:18h:57m:40s
169.254.0.1               server04          eth2                      44:38:39:00:05:06        default          no     2d:18h:57m:40s
169.254.0.1               spine01           swp1                      44:38:39:00:02:01        default          no     2d:19h:3m:27s
169.254.0.1               spine01           swp2                      44:38:39:00:03:01        default          no     2d:19h:3m:27s
169.254.0.1               spine01           swp3                      44:38:39:00:04:01        default          no     2d:19h:3m:28s
169.254.0.1               spine01           swp4                      44:38:39:00:05:01        default          no     2d:19h:3m:28s
169.254.0.1               spine02           swp1                      44:38:39:00:02:02        default          no     2d:19h:3m:27s
169.254.0.1               spine02           swp2                      44:38:39:00:03:02        default          no     2d:19h:3m:27s
169.254.0.1               spine02           swp3                      44:38:39:00:04:02        default          no     2d:19h:3m:27s
169.254.0.1               spine02           swp4                      44:38:39:00:05:02        default          no     2d:19h:3m:27s
192.168.0.11              oob-mgmt-server   eth1                      44:38:39:00:02:00        default          no     2d:19h:5m:48s
192.168.0.12              oob-mgmt-server   eth1                      44:38:39:00:03:00        default          no     2d:19h:5m:34s
192.168.0.13              oob-mgmt-server   eth1                      44:38:39:00:04:00        default          no     2d:19h:5m:34s
192.168.0.14              oob-mgmt-server   eth1                      44:38:39:00:05:00        default          no     2d:19h:7m:8s
192.168.0.21              oob-mgmt-server   eth1                      44:38:39:00:06:00        default          no     2d:19h:5m:36s
192.168.0.22              oob-mgmt-server   eth1                      44:38:39:00:07:00        default          no     2d:19h:5m:34s
192.168.0.254             leaf01            eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:9s
192.168.0.254             leaf02            eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:9s
192.168.0.254             leaf03            eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:8s
192.168.0.254             leaf04            eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:7s
192.168.0.254             server01          eth0                      44:38:39:00:01:01        default          no     2d:18h:57m:41s
192.168.0.254             server02          eth0                      44:38:39:00:01:01        default          no     2d:18h:57m:40s
192.168.0.254             server03          eth0                      44:38:39:00:01:01        default          no     2d:18h:57m:40s
192.168.0.254             server04          eth0                      44:38:39:00:01:01        default          no     2d:18h:57m:40s
192.168.0.254             spine01           eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:9s
192.168.0.254             spine02           eth0                      44:38:39:00:01:01        mgmt             no     2d:19h:4m:9s
192.168.0.31              oob-mgmt-server   eth1                      44:38:39:00:08:00        default          no     2d:19h:7m:8s
192.168.0.32              oob-mgmt-server   eth1                      44:38:39:00:09:00        default          no     2d:19h:7m:8s
192.168.0.33              oob-mgmt-server   eth1                      44:38:39:00:0a:00        default          no     2d:19h:7m:8s
192.168.0.34              oob-mgmt-server   eth1                      44:38:39:00:0b:00        default          no     2d:19h:7m:8s

```
## netq show ip route
```


Matching routes records:
Origin VRF              Prefix                         Hostname          Nexthops                         Last Changed
------ ---------------- ------------------------------ ----------------- -------------------------------- ----------------
no     default          0.0.0.0/0                      server04          192.168.0.254: eth0              1h:38m:15s
no     default          0.0.0.0/0                      server03          192.168.0.254: eth0              1h:38m:15s
no     default          0.0.0.0/0                      server01          192.168.0.254: eth0              1h:38m:5s
no     default          10.0.0.11/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.11/32                   server01          169.254.0.1: eth1                1h:38m:5s
no     default          10.0.0.11/32                   oob-mgmt-server   169.254.0.1: eth2                1h:38m:19s
no     default          10.0.0.11/32                   spine02           169.254.0.1: swp1                1h:38m:8s
no     default          10.0.0.11/32                   server02          169.254.0.1: eth1                1h:38m:12s
no     default          10.0.0.12/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.12/32                   spine01           169.254.0.1: swp2                1h:38m:19s
no     default          10.0.0.12/32                   leaf01            169.254.0.1: swp44,              1h:38m:21s
                                                                         169.254.0.1: swp51,
                                                                         169.254.0.1: swp52
no     default          10.0.0.12/32                   oob-mgmt-server   169.254.0.1: eth3                1h:38m:19s
no     default          10.0.0.12/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.13/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.13/32                   spine01           169.254.0.1: swp3                1h:38m:19s
no     default          10.0.0.13/32                   server04          169.254.0.1: eth1                1h:38m:15s
no     default          10.0.0.14/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.14/32                   spine01           169.254.0.1: swp4                1h:38m:19s
no     default          10.0.0.14/32                   leaf01            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.14/32                   spine02           169.254.0.1: swp4                1h:38m:8s
no     default          10.0.0.14/32                   server04          169.254.0.1: eth2                1h:38m:15s
no     default          10.0.0.21/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.21/32                   leaf03            169.254.0.1: swp51               1h:38m:19s
no     default          10.0.0.21/32                   leaf04            169.254.0.1: swp51               1h:38m:21s
no     default          10.0.0.21/32                   leaf01            169.254.0.1: swp51               1h:38m:21s
no     default          10.0.0.21/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   leaf03            169.254.0.1: swp52               1h:38m:19s
no     default          10.0.0.31/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.31/32                   leaf02            169.254.0.1: swp1                1h:38m:19s
no     default          10.0.0.31/32                   spine01           169.254.0.1: swp1,               1h:38m:19s
                                                                         169.254.0.1: swp2
no     default          10.0.0.31/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.31/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.32/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.32/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.32/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.32/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.33/32                   spine02           169.254.0.1: swp3,               1h:38m:8s
                                                                         169.254.0.1: swp4
no     default          10.0.0.33/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.33/32                   leaf02            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.33/32                   leaf03            169.254.0.1: swp1                1h:38m:19s
no     default          10.0.0.33/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.33/32                   leaf04            169.254.0.1: swp1                1h:38m:21s
no     default          10.0.0.34/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.34/32                   spine02           169.254.0.1: swp3,               1h:38m:8s
                                                                         169.254.0.1: swp4
no     default          10.0.0.34/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.34/32                   leaf02            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.34/32                   leaf03            169.254.0.1: swp2                1h:38m:19s
no     default          10.0.0.34/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.41/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.41/32                   leaf02            169.254.0.1: swp44               1h:38m:19s
no     default          10.0.0.41/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.41/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.41/32                   spine02           169.254.0.1: swp1,               1h:38m:8s
                                                                         169.254.0.1: swp2
no     default          10.0.0.41/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.41/32                   leaf01            169.254.0.1: swp44               1h:38m:21s
no     default          10.244.135.128/26              server04          Blackhole                        1h:36m:45s
no     default          10.244.135.128/26              oob-mgmt-server   169.254.0.1: eth2,               1h:36m:44s
                                                                         169.254.0.1: eth3
no     default          10.244.135.128/26              spine01           169.254.0.1: swp3,               1h:36m:44s
                                                                         169.254.0.1: swp4
no     default          10.244.135.137/32              server04          calia1512473e0b                  1h:36m:46s
no     default          10.244.135.138/32              server04          cali24ab13fd7c6                  1h:36m:36s
no     default          10.244.135.139/32              server04          calif3852dd8310                  1h:36m:35s
no     default          10.244.188.0/26                oob-mgmt-server   169.254.0.1: eth2,               1h:36m:5s
                                                                         169.254.0.1: eth3
no     default          10.244.188.0/26                leaf02            169.254.0.1: swp1                1h:36m:5s
no     default          10.244.188.0/26                server02          169.254.0.1: eth1,               1h:36m:5s
                                                                         169.254.0.1: eth2
no     default          10.244.188.0/26                leaf03            169.254.0.1: swp51,              1h:36m:5s
                                                                         169.254.0.1: swp52
no     default          10.244.188.6/32                server01          cali8ec1d1ccd89                  1h:36m:30s
no     default          10.244.40.192/26               leaf02            169.254.0.1: swp51,              1h:36m:45s
                                                                         169.254.0.1: swp52
no     default          10.244.40.192/26               server04          169.254.0.1: eth1,               1h:36m:45s
                                                                         169.254.0.1: eth2
no     default          10.244.40.192/26               server02          169.254.0.1: eth1,               1h:36m:45s
                                                                         169.254.0.1: eth2
no     default          10.244.40.192/26               server03          Blackhole                        1h:36m:45s
no     default          10.244.40.192/26               leaf01            169.254.0.1: swp51,              1h:36m:45s
                                                                         169.254.0.1: swp52
no     default          10.244.40.205/32               server03          cali6f7cd6a5112                  1h:36m:41s
no     default          10.244.40.206/32               server03          calic8efae22f6c                  1h:36m:40s
no     default          10.244.40.207/32               server03          cali76e21be405c                  1h:36m:38s
no     default          10.244.6.0/26                  server03          169.254.0.1: eth1,               1h:36m:54s
                                                                         169.254.0.1: eth2
no     default          10.244.6.0/26                  leaf03            169.254.0.1: swp51,              1h:36m:54s
                                                                         169.254.0.1: swp52
no     default          10.244.6.0/26                  oob-mgmt-server   169.254.0.1: eth2,               1h:36m:54s
                                                                         169.254.0.1: eth3
no     default          10.244.6.0/26                  spine02           169.254.0.1: swp1,               1h:36m:54s
                                                                         169.254.0.1: swp2
no     default          10.244.6.0/26                  server01          169.254.0.1: eth1,               1h:36m:54s
                                                                         169.254.0.1: eth2
no     default          10.244.6.0/26                  server02          Blackhole                        1h:36m:54s
no     default          10.244.6.10/32                 server02          cali1332f51f81b                  1h:36m:47s
no     default          10.244.6.11/32                 server02          cali6bb7f391314                  1h:36m:46s
no     default          10.244.6.9/32                  server02          calic0bf60df561                  1h:36m:47s
no     mgmt             0.0.0.0/0                      leaf02            Blackhole                        1h:38m:19s
no     mgmt             0.0.0.0/0                      leaf03            Blackhole                        1h:38m:19s
no     mgmt             0.0.0.0/0                      leaf04            192.168.0.254: eth0              1h:38m:21s
yes    default          10.0.0.21/32                   spine01           lo                               1h:38m:19s
yes    default          10.0.0.22/32                   spine02           lo                               1h:38m:8s
yes    default          10.0.0.33/32                   server03          lo                               1h:38m:15s
yes    default          10.255.0.0/16                  oob-mgmt-server   eth0                             1h:38m:19s
yes    default          172.18.0.0/16                  server02          cbr0                             1h:38m:12s
yes    default          192.168.0.0/16                 server02          eth0                             1h:38m:12s
yes    default          192.168.0.0/16                 server04          eth0                             1h:38m:15s
yes    default          192.168.0.254/32               oob-mgmt-server   eth1                             1h:38m:19s
yes    default          192.168.0.32/32                server02          eth0                             1h:38m:12s
yes    default          192.168.0.33/32                server03          eth0                             1h:38m:15s
yes    mgmt             192.168.0.0/16                 leaf01            eth0                             1h:38m:21s
yes    mgmt             192.168.0.0/16                 leaf03            eth0                             1h:38m:19s
yes    mgmt             192.168.0.0/16                 leaf02            eth0                             1h:38m:19s
yes    mgmt             192.168.0.0/16                 leaf04            eth0                             1h:38m:21s
yes    mgmt             192.168.0.22/32                spine02           eth0                             1h:38m:8s
no     default          0.0.0.0/0                      server02          192.168.0.254: eth0              1h:38m:12s
no     default          10.0.0.11/32                   spine01           169.254.0.1: swp1                1h:38m:19s
no     default          10.0.0.11/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.11/32                   leaf02            169.254.0.1: swp44,              1h:38m:19s
                                                                         169.254.0.1: swp51,
                                                                         169.254.0.1: swp52
no     default          10.0.0.11/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.11/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.12/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.12/32                   server01          169.254.0.1: eth2                1h:38m:5s
no     default          10.0.0.12/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.12/32                   spine02           169.254.0.1: swp2                1h:38m:8s
no     default          10.0.0.13/32                   spine02           169.254.0.1: swp3                1h:38m:8s
no     default          10.0.0.13/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.13/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.13/32                   leaf01            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.13/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.14/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.14/32                   server03          169.254.0.1: eth2                1h:38m:15s
no     default          10.0.0.21/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.21/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   leaf01            169.254.0.1: swp52               1h:38m:21s
no     default          10.0.0.22/32                   leaf02            169.254.0.1: swp52               1h:38m:19s
no     default          10.0.0.22/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.31/32                   leaf01            169.254.0.1: swp1                1h:38m:21s
no     default          10.0.0.31/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.31/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.32/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.32/32                   leaf02            169.254.0.1: swp2                1h:38m:19s
no     default          10.0.0.32/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.32/32                   spine01           169.254.0.1: swp1,               1h:38m:19s
                                                                         169.254.0.1: swp2
no     default          10.0.0.33/32                   spine01           169.254.0.1: swp3,               1h:38m:19s
                                                                         169.254.0.1: swp4
no     default          10.0.0.33/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.33/32                   leaf01            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.33/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.34/32                   leaf01            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.34/32                   spine01           169.254.0.1: swp3,               1h:38m:19s
                                                                         169.254.0.1: swp4
no     default          10.0.0.34/32                   leaf04            169.254.0.1: swp2                1h:38m:21s
no     default          10.0.0.34/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.41/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.41/32                   spine01           169.254.0.1: swp1,               1h:38m:19s
                                                                         169.254.0.1: swp2
no     default          10.0.0.41/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.244.135.128/26              leaf01            169.254.0.1: swp51,              1h:36m:44s
                                                                         169.254.0.1: swp52
no     default          10.244.135.128/26              server03          169.254.0.1: eth1,               1h:36m:45s
                                                                         169.254.0.1: eth2
no     default          10.244.135.128/26              leaf03            169.254.0.1: swp2                1h:36m:45s
no     default          10.244.135.128/26              leaf04            169.254.0.1: swp2                1h:36m:45s
no     default          10.244.135.128/26              server02          169.254.0.1: eth1,               1h:36m:44s
                                                                         169.254.0.1: eth2
no     default          10.244.135.128/26              leaf02            169.254.0.1: swp51,              1h:36m:44s
                                                                         169.254.0.1: swp52
no     default          10.244.188.0/26                leaf01            169.254.0.1: swp1                1h:36m:5s
no     default          10.244.188.0/26                server04          169.254.0.1: eth1,               1h:36m:5s
                                                                         169.254.0.1: eth2
no     default          10.244.188.0/26                server03          169.254.0.1: eth1,               1h:36m:5s
                                                                         169.254.0.1: eth2
no     default          10.244.188.0/26                leaf04            169.254.0.1: swp51,              1h:36m:5s
                                                                         169.254.0.1: swp52
no     default          10.244.188.0/26                server01          Blackhole                        1h:36m:5s
no     default          10.244.188.0/26                spine02           169.254.0.1: swp1,               1h:36m:5s
                                                                         169.254.0.1: swp2
no     default          10.244.188.7/32                server01          cali41761d66072                  1h:36m:29s
no     default          10.244.40.192/26               spine01           169.254.0.1: swp3,               1h:36m:45s
                                                                         169.254.0.1: swp4
no     default          10.244.40.192/26               server01          169.254.0.1: eth1,               1h:36m:45s
                                                                         169.254.0.1: eth2
no     default          10.244.40.192/26               leaf04            169.254.0.1: swp1                1h:36m:45s
no     default          10.244.40.192/26               leaf03            169.254.0.1: swp1                1h:36m:45s
no     default          10.244.40.192/26               oob-mgmt-server   169.254.0.1: eth2,               1h:36m:45s
                                                                         169.254.0.1: eth3
no     default          10.244.40.192/26               spine02           169.254.0.1: swp3,               1h:36m:45s
                                                                         169.254.0.1: swp4
no     default          10.244.40.204/32               server03          calid4504ded79f                  1h:36m:43s
no     default          10.244.6.0/26                  leaf04            169.254.0.1: swp51,              1h:36m:54s
                                                                         169.254.0.1: swp52
no     default          10.244.6.0/26                  spine01           169.254.0.1: swp1,               1h:36m:54s
                                                                         169.254.0.1: swp2
no     default          10.244.6.0/26                  leaf02            169.254.0.1: swp2                1h:36m:54s
no     mgmt             0.0.0.0/0                      spine01           Blackhole                        1h:38m:19s
no     mgmt             0.0.0.0/0                      leaf01            Blackhole                        1h:38m:21s
no     mgmt             0.0.0.0/0                      leaf01            192.168.0.254: eth0              1h:38m:22s
no     mgmt             0.0.0.0/0                      leaf02            192.168.0.254: eth0              1h:38m:19s
no     mgmt             0.0.0.0/0                      leaf03            192.168.0.254: eth0              1h:38m:19s
no     mgmt             0.0.0.0/0                      spine02           Blackhole                        1h:38m:8s
no     mgmt             0.0.0.0/0                      leaf04            Blackhole                        1h:38m:21s
no     mgmt             0.0.0.0/0                      spine02           192.168.0.254: eth0              1h:38m:8s
yes    default          10.0.0.11/32                   leaf01            lo                               1h:38m:21s
yes    default          10.0.0.12/32                   leaf02            lo                               1h:38m:19s
yes    default          10.0.0.13/32                   leaf03            lo                               1h:38m:19s
yes    default          10.0.0.14/32                   leaf04            lo                               1h:38m:21s
yes    default          10.0.0.31/32                   server01          lo                               1h:38m:5s
yes    default          10.0.0.41/32                   oob-mgmt-server   lo                               1h:38m:19s
yes    default          10.255.0.1/32                  oob-mgmt-server   eth0                             1h:38m:19s
yes    default          172.17.0.0/16                  oob-mgmt-server   docker0                          1h:38m:19s
yes    default          172.17.0.1/32                  oob-mgmt-server   docker0                          1h:38m:19s
yes    default          172.18.0.0/16                  server03          cbr0                             1h:38m:15s
yes    default          172.18.0.0/16                  server01          cbr0                             1h:38m:5s
yes    default          172.18.0.0/16                  server04          cbr0                             1h:38m:15s
yes    default          172.18.0.1/32                  server03          cbr0                             1h:38m:15s
yes    default          172.18.0.1/32                  server02          cbr0                             1h:38m:12s
yes    default          172.18.0.1/32                  server04          cbr0                             1h:38m:15s
yes    default          172.18.0.1/32                  server01          cbr0                             1h:38m:5s
yes    default          192.168.0.0/16                 server01          eth0                             1h:38m:5s
yes    default          192.168.0.0/16                 oob-mgmt-server   eth1                             1h:38m:19s
yes    default          192.168.0.31/32                server01          eth0                             1h:38m:5s
yes    default          192.168.0.34/32                server04          eth0                             1h:38m:15s
yes    mgmt             192.168.0.0/16                 spine02           eth0                             1h:38m:8s
yes    mgmt             192.168.0.0/16                 spine01           eth0                             1h:38m:19s
yes    mgmt             192.168.0.11/32                leaf01            eth0                             1h:38m:21s
yes    mgmt             192.168.0.12/32                leaf02            eth0                             1h:38m:19s
yes    mgmt             192.168.0.13/32                leaf03            eth0                             1h:38m:19s
yes    mgmt             192.168.0.14/32                leaf04            eth0                             1h:38m:21s
yes    mgmt             192.168.0.21/32                spine01           eth0                             1h:38m:19s
no     default          0.0.0.0/0                      oob-mgmt-server   10.255.0.3: eth0                 1h:38m:19s
no     default          10.0.0.12/32                   server02          169.254.0.1: eth2                1h:38m:12s
no     default          10.0.0.13/32                   leaf02            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.13/32                   server03          169.254.0.1: eth1                1h:38m:15s
no     default          10.0.0.14/32                   leaf02            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.14/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.14/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.21/32                   leaf02            169.254.0.1: swp51               1h:38m:19s
no     default          10.0.0.21/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   leaf04            169.254.0.1: swp52               1h:38m:21s
no     default          10.0.0.22/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.31/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.31/32                   spine02           169.254.0.1: swp1,               1h:38m:8s
                                                                         169.254.0.1: swp2
no     default          10.0.0.32/32                   leaf01            169.254.0.1: swp2                1h:38m:21s
no     default          10.0.0.32/32                   spine02           169.254.0.1: swp1,               1h:38m:8s
                                                                         169.254.0.1: swp2
no     default          10.244.135.128/26              spine02           169.254.0.1: swp3,               1h:36m:45s
                                                                         169.254.0.1: swp4
no     default          10.244.135.128/26              server01          169.254.0.1: eth1,               1h:36m:44s
                                                                         169.254.0.1: eth2
no     default          10.244.188.0/26                spine01           169.254.0.1: swp1,               1h:36m:5s
                                                                         169.254.0.1: swp2
no     default          10.244.6.0/26                  leaf01            169.254.0.1: swp2                1h:36m:54s
no     default          10.244.6.0/26                  server04          169.254.0.1: eth1,               1h:36m:54s
                                                                         169.254.0.1: eth2
no     mgmt             0.0.0.0/0                      spine01           192.168.0.254: eth0              1h:38m:19s
yes    default          10.0.0.32/32                   server02          lo                               1h:38m:12s
yes    default          10.0.0.34/32                   server04          lo                               1h:38m:15s
yes    default          192.168.0.0/16                 server03          eth0                             1h:38m:15s

```
```

The following commands contain keyword(s) 'show', 'ip', 'route'

    netq [<hostname>] show ip routes [<ipv4>|<ipv4/prefixlen>] [origin] [count] [json]
    netq [<hostname>] show ip routes [<ipv4>|<ipv4/prefixlen>] [origin] around <text-time> [count] [json]
    netq [<hostname>] show ip routes [<ipv4>|<ipv4/prefixlen>] [origin] changes [json]
    netq [<hostname>] show ip routes [<ipv4>|<ipv4/prefixlen>] [origin] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show ip routes [<ipv4>|<ipv4/prefixlen>] vrf <vrf> [origin] [count] [json]
    netq [<hostname>] show ip routes [<ipv4>|<ipv4/prefixlen>] vrf <vrf> [origin] around <text-time> [count] [json]
    netq [<hostname>] show ip routes [<ipv4>|<ipv4/prefixlen>] vrf <vrf> [origin] changes [json]
    netq [<hostname>] show ip routes [<ipv4>|<ipv4/prefixlen>] vrf <vrf> [origin] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show ipv6 routes [<ipv6>|<ipv6/prefixlen>] [origin] [count] [json]
    netq [<hostname>] show ipv6 routes [<ipv6>|<ipv6/prefixlen>] [origin] around <text-time> [count] [json]
    netq [<hostname>] show ipv6 routes [<ipv6>|<ipv6/prefixlen>] [origin] changes [json]
    netq [<hostname>] show ipv6 routes [<ipv6>|<ipv6/prefixlen>] [origin] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show ipv6 routes [<ipv6>|<ipv6/prefixlen>] vrf <vrf> [origin] [count] [json]
    netq [<hostname>] show ipv6 routes [<ipv6>|<ipv6/prefixlen>] vrf <vrf> [origin] around <text-time> [count] [json]
    netq [<hostname>] show ipv6 routes [<ipv6>|<ipv6/prefixlen>] vrf <vrf> [origin] changes [json]
    netq [<hostname>] show ipv6 routes [<ipv6>|<ipv6/prefixlen>] vrf <vrf> [origin] changes between <text-time> and <text-endtime> [json]


Unable to find command netq show ip route --help


Matching routes records:
Origin VRF              Prefix                         Hostname          Nexthops                         Last Changed
------ ---------------- ------------------------------ ----------------- -------------------------------- ----------------
no     default          0.0.0.0/0                      server04          192.168.0.254: eth0              1h:38m:15s
no     default          0.0.0.0/0                      server03          192.168.0.254: eth0              1h:38m:15s
no     default          0.0.0.0/0                      server01          192.168.0.254: eth0              1h:38m:5s
no     default          10.0.0.11/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.11/32                   server01          169.254.0.1: eth1                1h:38m:5s
no     default          10.0.0.11/32                   oob-mgmt-server   169.254.0.1: eth2                1h:38m:19s
no     default          10.0.0.11/32                   spine02           169.254.0.1: swp1                1h:38m:8s
no     default          10.0.0.11/32                   server02          169.254.0.1: eth1                1h:38m:12s
no     default          10.0.0.12/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.12/32                   spine01           169.254.0.1: swp2                1h:38m:19s
no     default          10.0.0.12/32                   leaf01            169.254.0.1: swp44,              1h:38m:21s
                                                                         169.254.0.1: swp51,
                                                                         169.254.0.1: swp52
no     default          10.0.0.12/32                   oob-mgmt-server   169.254.0.1: eth3                1h:38m:19s
no     default          10.0.0.12/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.13/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.13/32                   spine01           169.254.0.1: swp3                1h:38m:19s
no     default          10.0.0.13/32                   server04          169.254.0.1: eth1                1h:38m:15s
no     default          10.0.0.14/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.14/32                   spine01           169.254.0.1: swp4                1h:38m:19s
no     default          10.0.0.14/32                   leaf01            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.14/32                   spine02           169.254.0.1: swp4                1h:38m:8s
no     default          10.0.0.14/32                   server04          169.254.0.1: eth2                1h:38m:15s
no     default          10.0.0.21/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.21/32                   leaf03            169.254.0.1: swp51               1h:38m:19s
no     default          10.0.0.21/32                   leaf04            169.254.0.1: swp51               1h:38m:21s
no     default          10.0.0.21/32                   leaf01            169.254.0.1: swp51               1h:38m:21s
no     default          10.0.0.21/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   leaf03            169.254.0.1: swp52               1h:38m:19s
no     default          10.0.0.31/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.31/32                   leaf02            169.254.0.1: swp1                1h:38m:19s
no     default          10.0.0.31/32                   spine01           169.254.0.1: swp1,               1h:38m:19s
                                                                         169.254.0.1: swp2
no     default          10.0.0.31/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.31/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.32/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.32/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.32/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.32/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.33/32                   spine02           169.254.0.1: swp3,               1h:38m:8s
                                                                         169.254.0.1: swp4
no     default          10.0.0.33/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.33/32                   leaf02            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.33/32                   leaf03            169.254.0.1: swp1                1h:38m:19s
no     default          10.0.0.33/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.33/32                   leaf04            169.254.0.1: swp1                1h:38m:21s
no     default          10.0.0.34/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.34/32                   spine02           169.254.0.1: swp3,               1h:38m:8s
                                                                         169.254.0.1: swp4
no     default          10.0.0.34/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.34/32                   leaf02            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.34/32                   leaf03            169.254.0.1: swp2                1h:38m:19s
no     default          10.0.0.34/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.41/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.41/32                   leaf02            169.254.0.1: swp44               1h:38m:19s
no     default          10.0.0.41/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.41/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.41/32                   spine02           169.254.0.1: swp1,               1h:38m:8s
                                                                         169.254.0.1: swp2
no     default          10.0.0.41/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.41/32                   leaf01            169.254.0.1: swp44               1h:38m:21s
no     default          10.244.135.128/26              server04          Blackhole                        1h:36m:45s
no     default          10.244.135.128/26              oob-mgmt-server   169.254.0.1: eth2,               1h:36m:44s
                                                                         169.254.0.1: eth3
no     default          10.244.135.128/26              spine01           169.254.0.1: swp3,               1h:36m:44s
                                                                         169.254.0.1: swp4
no     default          10.244.135.137/32              server04          calia1512473e0b                  1h:36m:46s
no     default          10.244.135.138/32              server04          cali24ab13fd7c6                  1h:36m:36s
no     default          10.244.135.139/32              server04          calif3852dd8310                  1h:36m:35s
no     default          10.244.188.0/26                oob-mgmt-server   169.254.0.1: eth2,               1h:36m:5s
                                                                         169.254.0.1: eth3
no     default          10.244.188.0/26                leaf02            169.254.0.1: swp1                1h:36m:5s
no     default          10.244.188.0/26                server02          169.254.0.1: eth1,               1h:36m:5s
                                                                         169.254.0.1: eth2
no     default          10.244.188.0/26                leaf03            169.254.0.1: swp51,              1h:36m:5s
                                                                         169.254.0.1: swp52
no     default          10.244.188.6/32                server01          cali8ec1d1ccd89                  1h:36m:30s
no     default          10.244.40.192/26               leaf02            169.254.0.1: swp51,              1h:36m:45s
                                                                         169.254.0.1: swp52
no     default          10.244.40.192/26               server04          169.254.0.1: eth1,               1h:36m:45s
                                                                         169.254.0.1: eth2
no     default          10.244.40.192/26               server02          169.254.0.1: eth1,               1h:36m:45s
                                                                         169.254.0.1: eth2
no     default          10.244.40.192/26               server03          Blackhole                        1h:36m:45s
no     default          10.244.40.192/26               leaf01            169.254.0.1: swp51,              1h:36m:45s
                                                                         169.254.0.1: swp52
no     default          10.244.40.205/32               server03          cali6f7cd6a5112                  1h:36m:41s
no     default          10.244.40.206/32               server03          calic8efae22f6c                  1h:36m:40s
no     default          10.244.40.207/32               server03          cali76e21be405c                  1h:36m:38s
no     default          10.244.6.0/26                  server03          169.254.0.1: eth1,               1h:36m:54s
                                                                         169.254.0.1: eth2
no     default          10.244.6.0/26                  leaf03            169.254.0.1: swp51,              1h:36m:54s
                                                                         169.254.0.1: swp52
no     default          10.244.6.0/26                  oob-mgmt-server   169.254.0.1: eth2,               1h:36m:54s
                                                                         169.254.0.1: eth3
no     default          10.244.6.0/26                  spine02           169.254.0.1: swp1,               1h:36m:54s
                                                                         169.254.0.1: swp2
no     default          10.244.6.0/26                  server01          169.254.0.1: eth1,               1h:36m:54s
                                                                         169.254.0.1: eth2
no     default          10.244.6.0/26                  server02          Blackhole                        1h:36m:54s
no     default          10.244.6.10/32                 server02          cali1332f51f81b                  1h:36m:47s
no     default          10.244.6.11/32                 server02          cali6bb7f391314                  1h:36m:46s
no     default          10.244.6.9/32                  server02          calic0bf60df561                  1h:36m:47s
no     mgmt             0.0.0.0/0                      leaf02            Blackhole                        1h:38m:19s
no     mgmt             0.0.0.0/0                      leaf03            Blackhole                        1h:38m:19s
no     mgmt             0.0.0.0/0                      leaf04            192.168.0.254: eth0              1h:38m:21s
yes    default          10.0.0.21/32                   spine01           lo                               1h:38m:19s
yes    default          10.0.0.22/32                   spine02           lo                               1h:38m:8s
yes    default          10.0.0.33/32                   server03          lo                               1h:38m:15s
yes    default          10.255.0.0/16                  oob-mgmt-server   eth0                             1h:38m:19s
yes    default          172.18.0.0/16                  server02          cbr0                             1h:38m:12s
yes    default          192.168.0.0/16                 server02          eth0                             1h:38m:12s
yes    default          192.168.0.0/16                 server04          eth0                             1h:38m:15s
yes    default          192.168.0.254/32               oob-mgmt-server   eth1                             1h:38m:19s
yes    default          192.168.0.32/32                server02          eth0                             1h:38m:12s
yes    default          192.168.0.33/32                server03          eth0                             1h:38m:15s
yes    mgmt             192.168.0.0/16                 leaf01            eth0                             1h:38m:21s
yes    mgmt             192.168.0.0/16                 leaf03            eth0                             1h:38m:19s
yes    mgmt             192.168.0.0/16                 leaf02            eth0                             1h:38m:19s
yes    mgmt             192.168.0.0/16                 leaf04            eth0                             1h:38m:21s
yes    mgmt             192.168.0.22/32                spine02           eth0                             1h:38m:8s
no     default          0.0.0.0/0                      server02          192.168.0.254: eth0              1h:38m:12s
no     default          10.0.0.11/32                   spine01           169.254.0.1: swp1                1h:38m:19s
no     default          10.0.0.11/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.11/32                   leaf02            169.254.0.1: swp44,              1h:38m:19s
                                                                         169.254.0.1: swp51,
                                                                         169.254.0.1: swp52
no     default          10.0.0.11/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.11/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.12/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.12/32                   server01          169.254.0.1: eth2                1h:38m:5s
no     default          10.0.0.12/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.12/32                   spine02           169.254.0.1: swp2                1h:38m:8s
no     default          10.0.0.13/32                   spine02           169.254.0.1: swp3                1h:38m:8s
no     default          10.0.0.13/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.13/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.13/32                   leaf01            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.13/32                   leaf04            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.14/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.14/32                   server03          169.254.0.1: eth2                1h:38m:15s
no     default          10.0.0.21/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.21/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   leaf01            169.254.0.1: swp52               1h:38m:21s
no     default          10.0.0.22/32                   leaf02            169.254.0.1: swp52               1h:38m:19s
no     default          10.0.0.22/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.31/32                   leaf01            169.254.0.1: swp1                1h:38m:21s
no     default          10.0.0.31/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.31/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.32/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.32/32                   leaf02            169.254.0.1: swp2                1h:38m:19s
no     default          10.0.0.32/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.32/32                   spine01           169.254.0.1: swp1,               1h:38m:19s
                                                                         169.254.0.1: swp2
no     default          10.0.0.33/32                   spine01           169.254.0.1: swp3,               1h:38m:19s
                                                                         169.254.0.1: swp4
no     default          10.0.0.33/32                   server02          169.254.0.1: eth1,               1h:38m:12s
                                                                         169.254.0.1: eth2
no     default          10.0.0.33/32                   leaf01            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.33/32                   oob-mgmt-server   169.254.0.1: eth2,               1h:38m:19s
                                                                         169.254.0.1: eth3
no     default          10.0.0.34/32                   leaf01            169.254.0.1: swp51,              1h:38m:21s
                                                                         169.254.0.1: swp52
no     default          10.0.0.34/32                   spine01           169.254.0.1: swp3,               1h:38m:19s
                                                                         169.254.0.1: swp4
no     default          10.0.0.34/32                   leaf04            169.254.0.1: swp2                1h:38m:21s
no     default          10.0.0.34/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.41/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.41/32                   spine01           169.254.0.1: swp1,               1h:38m:19s
                                                                         169.254.0.1: swp2
no     default          10.0.0.41/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.244.135.128/26              leaf01            169.254.0.1: swp51,              1h:36m:44s
                                                                         169.254.0.1: swp52
no     default          10.244.135.128/26              server03          169.254.0.1: eth1,               1h:36m:45s
                                                                         169.254.0.1: eth2
no     default          10.244.135.128/26              leaf03            169.254.0.1: swp2                1h:36m:45s
no     default          10.244.135.128/26              leaf04            169.254.0.1: swp2                1h:36m:45s
no     default          10.244.135.128/26              server02          169.254.0.1: eth1,               1h:36m:44s
                                                                         169.254.0.1: eth2
no     default          10.244.135.128/26              leaf02            169.254.0.1: swp51,              1h:36m:44s
                                                                         169.254.0.1: swp52
no     default          10.244.188.0/26                leaf01            169.254.0.1: swp1                1h:36m:5s
no     default          10.244.188.0/26                server04          169.254.0.1: eth1,               1h:36m:5s
                                                                         169.254.0.1: eth2
no     default          10.244.188.0/26                server03          169.254.0.1: eth1,               1h:36m:5s
                                                                         169.254.0.1: eth2
no     default          10.244.188.0/26                leaf04            169.254.0.1: swp51,              1h:36m:5s
                                                                         169.254.0.1: swp52
no     default          10.244.188.0/26                server01          Blackhole                        1h:36m:5s
no     default          10.244.188.0/26                spine02           169.254.0.1: swp1,               1h:36m:5s
                                                                         169.254.0.1: swp2
no     default          10.244.188.7/32                server01          cali41761d66072                  1h:36m:29s
no     default          10.244.40.192/26               spine01           169.254.0.1: swp3,               1h:36m:45s
                                                                         169.254.0.1: swp4
no     default          10.244.40.192/26               server01          169.254.0.1: eth1,               1h:36m:45s
                                                                         169.254.0.1: eth2
no     default          10.244.40.192/26               leaf04            169.254.0.1: swp1                1h:36m:45s
no     default          10.244.40.192/26               leaf03            169.254.0.1: swp1                1h:36m:45s
no     default          10.244.40.192/26               oob-mgmt-server   169.254.0.1: eth2,               1h:36m:45s
                                                                         169.254.0.1: eth3
no     default          10.244.40.192/26               spine02           169.254.0.1: swp3,               1h:36m:45s
                                                                         169.254.0.1: swp4
no     default          10.244.40.204/32               server03          calid4504ded79f                  1h:36m:43s
no     default          10.244.6.0/26                  leaf04            169.254.0.1: swp51,              1h:36m:54s
                                                                         169.254.0.1: swp52
no     default          10.244.6.0/26                  spine01           169.254.0.1: swp1,               1h:36m:54s
                                                                         169.254.0.1: swp2
no     default          10.244.6.0/26                  leaf02            169.254.0.1: swp2                1h:36m:54s
no     mgmt             0.0.0.0/0                      spine01           Blackhole                        1h:38m:19s
no     mgmt             0.0.0.0/0                      leaf01            Blackhole                        1h:38m:21s
no     mgmt             0.0.0.0/0                      leaf01            192.168.0.254: eth0              1h:38m:22s
no     mgmt             0.0.0.0/0                      leaf02            192.168.0.254: eth0              1h:38m:19s
no     mgmt             0.0.0.0/0                      leaf03            192.168.0.254: eth0              1h:38m:19s
no     mgmt             0.0.0.0/0                      spine02           Blackhole                        1h:38m:8s
no     mgmt             0.0.0.0/0                      leaf04            Blackhole                        1h:38m:21s
no     mgmt             0.0.0.0/0                      spine02           192.168.0.254: eth0              1h:38m:8s
yes    default          10.0.0.11/32                   leaf01            lo                               1h:38m:21s
yes    default          10.0.0.12/32                   leaf02            lo                               1h:38m:19s
yes    default          10.0.0.13/32                   leaf03            lo                               1h:38m:19s
yes    default          10.0.0.14/32                   leaf04            lo                               1h:38m:21s
yes    default          10.0.0.31/32                   server01          lo                               1h:38m:5s
yes    default          10.0.0.41/32                   oob-mgmt-server   lo                               1h:38m:19s
yes    default          10.255.0.1/32                  oob-mgmt-server   eth0                             1h:38m:19s
yes    default          172.17.0.0/16                  oob-mgmt-server   docker0                          1h:38m:19s
yes    default          172.17.0.1/32                  oob-mgmt-server   docker0                          1h:38m:19s
yes    default          172.18.0.0/16                  server03          cbr0                             1h:38m:15s
yes    default          172.18.0.0/16                  server01          cbr0                             1h:38m:5s
yes    default          172.18.0.0/16                  server04          cbr0                             1h:38m:15s
yes    default          172.18.0.1/32                  server03          cbr0                             1h:38m:15s
yes    default          172.18.0.1/32                  server02          cbr0                             1h:38m:12s
yes    default          172.18.0.1/32                  server04          cbr0                             1h:38m:15s
yes    default          172.18.0.1/32                  server01          cbr0                             1h:38m:5s
yes    default          192.168.0.0/16                 server01          eth0                             1h:38m:5s
yes    default          192.168.0.0/16                 oob-mgmt-server   eth1                             1h:38m:19s
yes    default          192.168.0.31/32                server01          eth0                             1h:38m:5s
yes    default          192.168.0.34/32                server04          eth0                             1h:38m:15s
yes    mgmt             192.168.0.0/16                 spine02           eth0                             1h:38m:8s
yes    mgmt             192.168.0.0/16                 spine01           eth0                             1h:38m:19s
yes    mgmt             192.168.0.11/32                leaf01            eth0                             1h:38m:21s
yes    mgmt             192.168.0.12/32                leaf02            eth0                             1h:38m:19s
yes    mgmt             192.168.0.13/32                leaf03            eth0                             1h:38m:19s
yes    mgmt             192.168.0.14/32                leaf04            eth0                             1h:38m:21s
yes    mgmt             192.168.0.21/32                spine01           eth0                             1h:38m:19s
no     default          0.0.0.0/0                      oob-mgmt-server   10.255.0.3: eth0                 1h:38m:19s
no     default          10.0.0.12/32                   server02          169.254.0.1: eth2                1h:38m:12s
no     default          10.0.0.13/32                   leaf02            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.13/32                   server03          169.254.0.1: eth1                1h:38m:15s
no     default          10.0.0.14/32                   leaf02            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.14/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.14/32                   leaf03            169.254.0.1: swp51,              1h:38m:19s
                                                                         169.254.0.1: swp52
no     default          10.0.0.21/32                   leaf02            169.254.0.1: swp51               1h:38m:19s
no     default          10.0.0.21/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   leaf04            169.254.0.1: swp52               1h:38m:21s
no     default          10.0.0.22/32                   server01          169.254.0.1: eth1,               1h:38m:5s
                                                                         169.254.0.1: eth2
no     default          10.0.0.22/32                   server04          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.31/32                   server03          169.254.0.1: eth1,               1h:38m:15s
                                                                         169.254.0.1: eth2
no     default          10.0.0.31/32                   spine02           169.254.0.1: swp1,               1h:38m:8s
                                                                         169.254.0.1: swp2
no     default          10.0.0.32/32                   leaf01            169.254.0.1: swp2                1h:38m:21s
no     default          10.0.0.32/32                   spine02           169.254.0.1: swp1,               1h:38m:8s
                                                                         169.254.0.1: swp2
no     default          10.244.135.128/26              spine02           169.254.0.1: swp3,               1h:36m:45s
                                                                         169.254.0.1: swp4
no     default          10.244.135.128/26              server01          169.254.0.1: eth1,               1h:36m:44s
                                                                         169.254.0.1: eth2
no     default          10.244.188.0/26                spine01           169.254.0.1: swp1,               1h:36m:5s
                                                                         169.254.0.1: swp2
no     default          10.244.6.0/26                  leaf01            169.254.0.1: swp2                1h:36m:54s
no     default          10.244.6.0/26                  server04          169.254.0.1: eth1,               1h:36m:54s
                                                                         169.254.0.1: eth2
no     mgmt             0.0.0.0/0                      spine01           192.168.0.254: eth0              1h:38m:19s
yes    default          10.0.0.32/32                   server02          lo                               1h:38m:12s
yes    default          10.0.0.34/32                   server04          lo                               1h:38m:15s
yes    default          192.168.0.0/16                 server03          eth0                             1h:38m:15s

```
