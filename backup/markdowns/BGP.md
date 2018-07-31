# BGP
## netq show bgp
```


Matching bgp records:
Hostname          Neighbor                         VRF              ASN        Peer ASN   PfxRx        Last Changed
----------------- -------------------------------- ---------------- ---------- ---------- ------------ ----------------
leaf01            swp1(server01)                   default          65011      65031      2/6/-        1h:41m:25s
leaf01            swp2(server02)                   default          65011      65032      2/1/-        1h:41m:31s
leaf01            swp44(oob-mgmt-server)           default          65011      65041      4/4/-        1h:41m:52s
leaf01            swp51(spine01)                   default          65011      65020      9/5/-        1h:42m:1s
leaf01            swp52(spine02)                   default          65011      65020      9/5/-        1h:41m:51s
leaf02            swp1(server01)                   default          65012      65031      2/1/-        1h:41m:26s
leaf02            swp2(server02)                   default          65012      65032      2/6/-        1h:41m:24s
leaf02            swp44(oob-mgmt-server)           default          65012      65041      12/4/-       1h:41m:55s
leaf02            swp51(spine01)                   default          65012      65020      12/4/-       1h:42m:7s
leaf02            swp52(spine02)                   default          65012      65020      12/4/-       1h:41m:54s
leaf03            swp1(server03)                   default          65013      65033      2/1/-        1h:41m:30s
leaf03            swp2(server04)                   default          65013      65034      2/1/-        1h:41m:29s
leaf03            swp51(spine01)                   default          65013      65020      10/5/-       1h:41m:42s
leaf03            swp52(spine02)                   default          65013      65020      9/5/-        1h:41m:40s
leaf04            swp1(server03)                   default          65014      65033      2/6/-        1h:41m:28s
leaf04            swp2(server04)                   default          65014      65034      2/6/-        1h:41m:27s
leaf04            swp51(spine01)                   default          65014      65020      12/5/-       1h:41m:32s
leaf04            swp52(spine02)                   default          65014      65020      13/5/-       1h:41m:39s
oob-mgmt-server   eth2(leaf01)                     default          65041      65011      14/6/-       1h:41m:52s
oob-mgmt-server   eth3(leaf02)                     default          65041      65012      14/6/-       1h:41m:54s
server01          eth1(leaf01)                     default          65031      65011      13/7/-       1h:41m:25s
server01          eth2(leaf02)                     default          65031      65012      13/7/-       1h:41m:25s
server02          eth1(leaf01)                     default          65032      65011      13/7/-       1h:41m:32s
server02          eth2(leaf02)                     default          65032      65012      13/7/-       1h:41m:24s
server03          eth1(leaf03)                     default          65033      65013      13/7/-       1h:41m:30s
server03          eth2(leaf04)                     default          65033      65014      13/7/-       1h:41m:29s
server04          eth1(leaf03)                     default          65034      65013      13/7/-       1h:41m:30s
server04          eth2(leaf04)                     default          65034      65014      13/7/-       1h:41m:27s
spine01           swp1(leaf01)                     default          65020      65011      6/2/-        1h:42m:3s
spine01           swp2(leaf02)                     default          65020      65012      6/2/-        1h:42m:7s
spine01           swp3(leaf03)                     default          65020      65013      5/1/-        1h:41m:43s
spine01           swp4(leaf04)                     default          65020      65014      5/1/-        1h:41m:33s
spine02           swp1(leaf01)                     default          65020      65011      6/2/-        1h:41m:52s
spine02           swp2(leaf02)                     default          65020      65012      6/2/-        1h:41m:54s
spine02           swp3(leaf03)                     default          65020      65013      5/1/-        1h:41m:40s
spine02           swp4(leaf04)                     default          65020      65014      5/1/-        1h:41m:40s

```
```

The following commands contain keyword(s) 'show', 'bgp'

    netq [<hostname>] show bgp <bgp-session> [json]
    netq [<hostname>] show bgp <bgp-session> around <text-time> [json]
    netq [<hostname>] show bgp <bgp-session> changes [json]
    netq [<hostname>] show bgp <bgp-session> changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show bgp <bgp-session> vrf <vrf> [json]
    netq [<hostname>] show bgp <bgp-session> vrf <vrf> around <text-time> [json]
    netq [<hostname>] show bgp <bgp-session> vrf <vrf> changes [json]
    netq [<hostname>] show bgp <bgp-session> vrf <vrf> changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show bgp [json]
    netq [<hostname>] show bgp around <text-time> [json]
    netq [<hostname>] show bgp asn <number-asn> [json]
    netq [<hostname>] show bgp asn <number-asn> around <text-time> [json]
    netq [<hostname>] show bgp asn <number-asn> changes [json]
    netq [<hostname>] show bgp asn <number-asn> changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show bgp asn <number-asn> vrf <vrf> [json]
    netq [<hostname>] show bgp asn <number-asn> vrf <vrf> around <text-time> [json]
    netq [<hostname>] show bgp asn <number-asn> vrf <vrf> changes [json]
    netq [<hostname>] show bgp asn <number-asn> vrf <vrf> changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show bgp changes [json]
    netq [<hostname>] show bgp changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show bgp vrf <vrf> [json]
    netq [<hostname>] show bgp vrf <vrf> around <text-time> [json]
    netq [<hostname>] show bgp vrf <vrf> changes [json]
    netq [<hostname>] show bgp vrf <vrf> changes between <text-time> and <text-endtime> [json]


Unable to find command netq show bgp --help


Matching bgp records:
Hostname          Neighbor                         VRF              ASN        Peer ASN   PfxRx        Last Changed
----------------- -------------------------------- ---------------- ---------- ---------- ------------ ----------------
leaf01            swp1(server01)                   default          65011      65031      2/6/-        1h:41m:25s
leaf01            swp2(server02)                   default          65011      65032      2/1/-        1h:41m:31s
leaf01            swp44(oob-mgmt-server)           default          65011      65041      4/4/-        1h:41m:52s
leaf01            swp51(spine01)                   default          65011      65020      9/5/-        1h:42m:1s
leaf01            swp52(spine02)                   default          65011      65020      9/5/-        1h:41m:51s
leaf02            swp1(server01)                   default          65012      65031      2/1/-        1h:41m:26s
leaf02            swp2(server02)                   default          65012      65032      2/6/-        1h:41m:24s
leaf02            swp44(oob-mgmt-server)           default          65012      65041      12/4/-       1h:41m:55s
leaf02            swp51(spine01)                   default          65012      65020      12/4/-       1h:42m:7s
leaf02            swp52(spine02)                   default          65012      65020      12/4/-       1h:41m:54s
leaf03            swp1(server03)                   default          65013      65033      2/1/-        1h:41m:30s
leaf03            swp2(server04)                   default          65013      65034      2/1/-        1h:41m:29s
leaf03            swp51(spine01)                   default          65013      65020      10/5/-       1h:41m:42s
leaf03            swp52(spine02)                   default          65013      65020      9/5/-        1h:41m:40s
leaf04            swp1(server03)                   default          65014      65033      2/6/-        1h:41m:28s
leaf04            swp2(server04)                   default          65014      65034      2/6/-        1h:41m:27s
leaf04            swp51(spine01)                   default          65014      65020      12/5/-       1h:41m:32s
leaf04            swp52(spine02)                   default          65014      65020      13/5/-       1h:41m:39s
oob-mgmt-server   eth2(leaf01)                     default          65041      65011      14/6/-       1h:41m:52s
oob-mgmt-server   eth3(leaf02)                     default          65041      65012      14/6/-       1h:41m:54s
server01          eth1(leaf01)                     default          65031      65011      13/7/-       1h:41m:25s
server01          eth2(leaf02)                     default          65031      65012      13/7/-       1h:41m:25s
server02          eth1(leaf01)                     default          65032      65011      13/7/-       1h:41m:32s
server02          eth2(leaf02)                     default          65032      65012      13/7/-       1h:41m:24s
server03          eth1(leaf03)                     default          65033      65013      13/7/-       1h:41m:30s
server03          eth2(leaf04)                     default          65033      65014      13/7/-       1h:41m:29s
server04          eth1(leaf03)                     default          65034      65013      13/7/-       1h:41m:30s
server04          eth2(leaf04)                     default          65034      65014      13/7/-       1h:41m:27s
spine01           swp1(leaf01)                     default          65020      65011      6/2/-        1h:42m:3s
spine01           swp2(leaf02)                     default          65020      65012      6/2/-        1h:42m:7s
spine01           swp3(leaf03)                     default          65020      65013      5/1/-        1h:41m:43s
spine01           swp4(leaf04)                     default          65020      65014      5/1/-        1h:41m:33s
spine02           swp1(leaf01)                     default          65020      65011      6/2/-        1h:41m:52s
spine02           swp2(leaf02)                     default          65020      65012      6/2/-        1h:41m:54s
spine02           swp3(leaf03)                     default          65020      65013      5/1/-        1h:41m:40s
spine02           swp4(leaf04)                     default          65020      65014      5/1/-        1h:41m:40s

```
## netq check bgp
```

[92mTotal Nodes: 11, Failed Nodes: 0, Total Sessions: 36, Failed Sessions: 0[0m

```
```

The following commands contain keyword(s) 'check', 'bgp'

    netq check bgp [json]
    netq check bgp around <text-time> [json]
    netq check bgp vrf <vrf> [json]
    netq check bgp vrf <vrf> around <text-time> [json]
    netq example check bgp


Unable to find command netq check bgp --help

[92mTotal Nodes: 11, Failed Nodes: 0, Total Sessions: 36, Failed Sessions: 0[0m

```
## net show bgp summary
```


show bgp ipv4 unicast summary
=============================
BGP router identifier 10.0.0.41, local AS number 65041 vrf-id 0
BGP table version 22
RIB entries 31, using 4712 bytes of memory
Peers 2, using 39 KiB of memory

Neighbor        V         AS MsgRcvd MsgSent   TblVer  InQ OutQ  Up/Down State/PfxRcd
leaf01(eth2)    4      65011    2069    2070        0    0    0 01:41:56           14
leaf02(eth3)    4      65012    2072    2073        0    0    0 01:41:58           14

Total number of neighbors 2


show bgp ipv6 unicast summary
=============================
BGP router identifier 10.0.0.41, local AS number 65041 vrf-id 0
BGP table version 10
RIB entries 13, using 1976 bytes of memory
Peers 2, using 39 KiB of memory

Neighbor        V         AS MsgRcvd MsgSent   TblVer  InQ OutQ  Up/Down State/PfxRcd
leaf01(eth2)    4      65011    2069    2070        0    0    0 01:41:57            6
leaf02(eth3)    4      65012    2072    2073        0    0    0 01:41:59            6

Total number of neighbors 2


show bgp l2vpn evpn summary
===========================

```
```

The following commands contain keyword(s) 'show', 'bgp', 'summary'

    net show bgp [l2vpn] evpn summary [json]
    net show bgp [summary] [json]
    net show bgp ipv4 (unicast|labeled-unicast) [<ipv4>|<ipv4/prefixlen>|summary] [json]
    net show bgp ipv6 (unicast|labeled-unicast) [<ipv6>|<ipv6/prefixlen>|summary] [json]
    net show bgp vrf <text> [summary] [json]
    net show bgp vrf <text> ipv4 unicast [<ipv4>|<ipv4/prefixlen>|summary] [json]
    net show bgp vrf <text> ipv6 unicast [<ipv6>|<ipv6/prefixlen>|summary] [json]


```
## net show bgp neighbor %DP
```

ERROR: Command not found

net show bgp neighbor %DP
                      ^ Invalid value here
Did you mean one of the following?

    net show bgp neighbor [94m[<bgppeer>][0m [json]

```
```

ERROR: There are no commands with keyword(s) 'show', 'bgp', 'neighbor', '%DP'

```
## net show evpn vni
```



```
```

The following commands contain keyword(s) 'show', 'evpn', 'vni'

    net show bgp [l2vpn] evpn route vni <1-16777215>
    net show bgp [l2vpn] evpn route vni <1-16777215> mac <mac>
    net show bgp [l2vpn] evpn route vni <1-16777215> mac <mac> ip <ip>
    net show bgp [l2vpn] evpn route vni <1-16777215> multicast <ipv4>
    net show bgp [l2vpn] evpn route vni <1-16777215> type (macip|multicast)
    net show bgp [l2vpn] evpn route vni <1-16777215> vtep <ipv4>
    net show bgp [l2vpn] evpn route vni all
    net show bgp [l2vpn] evpn route vni all vtep <ipv4>
    net show bgp [l2vpn] evpn vni [<1-16777215>]
    net show evpn arp-cache vni <1-16777215> [json]
    net show evpn arp-cache vni <1-16777215> ip <ip> [json]
    net show evpn arp-cache vni <1-16777215> vtep <ipv4> [json]
    net show evpn arp-cache vni all [json]
    net show evpn mac vni <1-16777215> [json]
    net show evpn mac vni <1-16777215> mac <mac>
    net show evpn mac vni <1-16777215> vtep <ipv4> [json]
    net show evpn mac vni all [json]
    net show evpn mac vni all vtep <ipv4> [json]
    net show evpn next-hops vni [<1-16777215>] [json]
    net show evpn next-hops vni [<1-16777215>] ip <ip> [json]
    net show evpn next-hops vni all [json]
    net show evpn rmac vni [<1-16777215>] [json]
    net show evpn rmac vni [<1-16777215>] mac <mac> [json]
    net show evpn rmac vni all [json]
    net show evpn vni [<1-16777215>] [json]


```
## net show evpn mac vni all
```



```
```

The following commands contain keyword(s) 'show', 'evpn', 'mac', 'vni', 'all'

    net show evpn mac vni all [json]
    net show evpn mac vni all vtep <ipv4> [json]


```
## net show bgp l2vpn evpn route
```

No EVPN prefixes exist

```
```

The following commands contain keyword(s) 'show', 'bgp', 'l2vpn', 'evpn', 'route'

    net show bgp [l2vpn] evpn route
    net show bgp [l2vpn] evpn route rd <rd>
    net show bgp [l2vpn] evpn route rd <rd> mac <mac>
    net show bgp [l2vpn] evpn route rd <rd> mac <mac> ip <ip>
    net show bgp [l2vpn] evpn route rd <rd> type (macip|multicast|prefix)
    net show bgp [l2vpn] evpn route type (macip|multicast|prefix)
    net show bgp [l2vpn] evpn route vni <1-16777215>
    net show bgp [l2vpn] evpn route vni <1-16777215> mac <mac>
    net show bgp [l2vpn] evpn route vni <1-16777215> mac <mac> ip <ip>
    net show bgp [l2vpn] evpn route vni <1-16777215> multicast <ipv4>
    net show bgp [l2vpn] evpn route vni <1-16777215> type (macip|multicast)
    net show bgp [l2vpn] evpn route vni <1-16777215> vtep <ipv4>
    net show bgp [l2vpn] evpn route vni all
    net show bgp [l2vpn] evpn route vni all vtep <ipv4>


```
## net show time
```

Thu Jul 19 19:50:00 UTC 2018

```
```

The following commands contain keyword(s) 'show', 'time'

    net show time [zone]
    net show time ntp servers


```
## net show time ntp servers
```

     remote           refid      st t when poll reach   delay   offset  jitter
==============================================================================
+mail.coldnortha 132.246.11.231   2 u   37  256  377   28.947   -4.432   1.413
*x.ns.gin.ntt.ne 249.224.99.213   2 u  114  256  377   11.047   -7.720   2.128
+helium.constant 128.59.0.245     2 u   33  256  377   28.069   -5.582   1.488
-paladin.latt.ne 204.123.2.72     2 u  188  256  245   51.685    1.358   1.155

```
```

The following commands contain keyword(s) 'show', 'time', 'ntp', 'servers'

    net show time ntp servers


```
## sudo systemctl status dhcrelay
```

● dhcrelay.service - DHCPv4 Relay Agent Daemon
   Loaded: loaded (/lib/systemd/system/dhcrelay.service; disabled)
   Active: inactive (dead)
     Docs: man:dhcrelay(8)

```
```

systemctl [OPTIONS...] {COMMAND} ...

Query or send control commands to the systemd manager.

  -h --help           Show this help
     --version        Show package version
     --system         Connect to system manager
     --user           Connect to user service manager
  -H --host=[USER@]HOST
                      Operate on remote host
  -M --machine=CONTAINER
                      Operate on local container
  -t --type=TYPE      List only units of a particular type
     --state=STATE    List only units with particular LOAD or SUB or ACTIVE state
  -p --property=NAME  Show only properties by this name
  -a --all            Show all loaded units/properties, including dead/empty
                      ones. To list all units installed on the system, use
                      the 'list-unit-files' command instead.
  -l --full           Don't ellipsize unit names on output
  -r --recursive      Show unit list of host and local containers
     --reverse        Show reverse dependencies with 'list-dependencies'
     --job-mode=MODE  Specify how to deal with already queued jobs, when
                      queueing a new job
     --show-types     When showing sockets, explicitly show their type
  -i --ignore-inhibitors
                      When shutting down or sleeping, ignore inhibitors
     --kill-who=WHO   Who to send signal to
  -s --signal=SIGNAL  Which signal to send
  -q --quiet          Suppress output
     --no-block       Do not wait until operation finished
     --no-wall        Don't send wall message before halt/power-off/reboot
     --no-reload      When enabling/disabling unit files, don't reload daemon
                      configuration
     --no-legend      Do not print a legend (column headers and hints)
     --no-pager       Do not pipe output into a pager
     --no-ask-password
                      Do not ask for system passwords
     --global         Enable/disable unit files globally
     --runtime        Enable unit files only temporarily until next reboot
  -f --force          When enabling unit files, override existing symlinks
                      When shutting down, execute action immediately
     --preset-mode=   Specifies whether fully apply presets, or only enable,
                      or only disable
     --root=PATH      Enable unit files in the specified root directory
  -n --lines=INTEGER  Number of journal entries to show
  -o --output=STRING  Change journal output mode (short, short-monotonic,
                      verbose, export, json, json-pretty, json-sse, cat)
     --plain          Print unit dependencies as a list instead of a tree

Unit Commands:
  list-units [PATTERN...]         List loaded units
  list-sockets [PATTERN...]       List loaded sockets ordered by address
  list-timers [PATTERN...]        List loaded timers ordered by next elapse
  start NAME...                   Start (activate) one or more units
  stop NAME...                    Stop (deactivate) one or more units
  reload NAME...                  Reload one or more units
  restart NAME...                 Start or restart one or more units
  try-restart NAME...             Restart one or more units if active
  reload-or-restart NAME...       Reload one or more units if possible,
                                  otherwise start or restart
  reload-or-try-restart NAME...   Reload one or more units if possible,
                                  otherwise restart if active
  isolate NAME                    Start one unit and stop all others
  kill NAME...                    Send signal to processes of a unit
  is-active PATTERN...            Check whether units are active
  is-failed PATTERN...            Check whether units are failed
  status [PATTERN...|PID...]      Show runtime status of one or more units
  show [PATTERN...|JOB...]        Show properties of one or more
                                  units/jobs or the manager
  cat PATTERN...                  Show files and drop-ins of one or more units
  set-property NAME ASSIGNMENT... Sets one or more properties of a unit
  help PATTERN...|PID...          Show manual for one or more units
  reset-failed [PATTERN...]       Reset failed state for all, one, or more
                                  units
  list-dependencies [NAME]        Recursively show units which are required
                                  or wanted by this unit or by which this
                                  unit is required or wanted

Unit File Commands:
  list-unit-files [PATTERN...]    List installed unit files
  enable NAME...                  Enable one or more unit files
  disable NAME...                 Disable one or more unit files
  reenable NAME...                Reenable one or more unit files
  preset NAME...                  Enable/disable one or more unit files
                                  based on preset configuration
  preset-all                      Enable/disable all unit files based on
                                  preset configuration
  is-enabled NAME...              Check whether unit files are enabled

  mask NAME...                    Mask one or more units
  unmask NAME...                  Unmask one or more units
  link PATH...                    Link one or more units files into
                                  the search path
  get-default                     Get the name of the default target
  set-default NAME                Set the default target

Machine Commands:
  list-machines [PATTERN...]      List local containers and host

Job Commands:
  list-jobs [PATTERN...]          List jobs
  cancel [JOB...]                 Cancel all, one, or more jobs

Snapshot Commands:
  snapshot [NAME]                 Create a snapshot
  delete NAME...                  Remove one or more snapshots

Environment Commands:
  show-environment                Dump environment
  set-environment NAME=VALUE...   Set one or more environment variables
  unset-environment NAME...       Unset one or more environment variables
  import-environment NAME...      Import all, one or more environment variables

Manager Lifecycle Commands:
  daemon-reload                   Reload systemd manager configuration
  daemon-reexec                   Reexecute systemd manager

System Commands:
  is-system-running               Check whether system is fully running
  default                         Enter system default mode
  rescue                          Enter system rescue mode
  emergency                       Enter system emergency mode
  halt                            Shut down and halt the system
  poweroff                        Shut down and power-off the system
  reboot [ARG]                    Shut down and reboot the system
  kexec                           Shut down and reboot the system with kexec
  exit                            Request user instance exit
  switch-root ROOT [INIT]         Change to a different root file system
  suspend                         Suspend the system
  hibernate                       Hibernate the system
  hybrid-sleep                    Hibernate and suspend the system

```
## net show bgp
```


show bgp ipv4 unicast
=====================
BGP table version is 22, local router ID is 10.0.0.41
Status codes: s suppressed, d damped, h history, * valid, > best, = multipath,
              i internal, r RIB-failure, S Stale, R Removed
Origin codes: i - IGP, e - EGP, ? - incomplete

   Network          Next Hop            Metric LocPrf Weight Path
*> 10.0.0.11/32     eth2                     0             0 65011 i
*                   eth3                                   0 65012 65020 65011 i
*  10.0.0.12/32     eth2                                   0 65011 65020 65012 i
*>                  eth3                     0             0 65012 i
*= 10.0.0.13/32     eth3                                   0 65012 65020 65013 i
*>                  eth2                                   0 65011 65020 65013 i
*= 10.0.0.14/32     eth3                                   0 65012 65020 65014 i
*>                  eth2                                   0 65011 65020 65014 i
*= 10.0.0.21/32     eth2                                   0 65011 65020 i
*>                  eth3                                   0 65012 65020 i
*= 10.0.0.22/32     eth2                                   0 65011 65020 i
*>                  eth3                                   0 65012 65020 i
*= 10.0.0.31/32     eth3                                   0 65012 65031 i
*>                  eth2                                   0 65011 65031 i
*= 10.0.0.32/32     eth3                                   0 65012 65032 i
*>                  eth2                                   0 65011 65032 i
*= 10.0.0.33/32     eth3                                   0 65012 65020 65013 65033 i
*>                  eth2                                   0 65011 65020 65013 65033 i
*> 10.0.0.34/32     eth2                                   0 65011 65020 65013 65034 i
*=                  eth3                                   0 65012 65020 65013 65034 i
*> 10.0.0.41/32     0.0.0.0                  0         32768 i
   10.0.2.0/24      0.0.0.0                  0         32768 i
*= 10.244.6.0/26    eth3                                   0 65012 65032 ?
*>                  eth2                                   0 65011 65032 ?
*= 10.244.40.192/26 eth3                                   0 65012 65020 65013 65033 ?
*>                  eth2                                   0 65011 65020 65013 65033 ?
*= 10.244.135.128/26
                    eth3                                   0 65012 65020 65014 65034 ?
*>                  eth2                                   0 65011 65020 65013 65034 ?
*> 10.244.188.0/26  eth2                                   0 65011 65031 ?
*=                  eth3                                   0 65012 65031 ?

Displayed  16 routes and 30 total paths


show bgp ipv6 unicast
=====================
BGP table version is 10, local router ID is 10.0.0.41
Status codes: s suppressed, d damped, h history, * valid, > best, = multipath,
              i internal, r RIB-failure, S Stale, R Removed
Origin codes: i - IGP, e - EGP, ? - incomplete

   Network          Next Hop            Metric LocPrf Weight Path
*> fd00::11/128     eth2                     0             0 65011 i
*                   eth3                                   0 65012 65020 65011 i
*  fd00::12/128     eth2                                   0 65011 65020 65012 i
*>                  eth3                     0             0 65012 i
*= fd00::13/128     eth3                                   0 65012 65020 65013 i
*>                  eth2                                   0 65011 65020 65013 i
*= fd00::14/128     eth3                                   0 65012 65020 65014 i
*>                  eth2                                   0 65011 65020 65014 i
*= fd00::21/128     eth2                                   0 65011 65020 i
*>                  eth3                                   0 65012 65020 i
*= fd00::22/128     eth2                                   0 65011 65020 i
*>                  eth3                                   0 65012 65020 i
*> fd00::41/128     ::                       0         32768 i

Displayed  7 routes and 13 total paths

```
```

The following commands contain keyword(s) 'show', 'bgp'

    net show bgp (<ipv4>|<ipv4/prefixlen>|<ipv6>|<ipv6/prefixlen>) [bestpath|multipath] [json]
    net show bgp (ipv4|ipv6) (unicast|labeled-unicast) neighbor <bgppeer> (advertised-routes|received-routes|routes) [json]
    net show bgp [l2vpn] evpn import-rt
    net show bgp [l2vpn] evpn route
    net show bgp [l2vpn] evpn route rd <rd>
    net show bgp [l2vpn] evpn route rd <rd> mac <mac>
    net show bgp [l2vpn] evpn route rd <rd> mac <mac> ip <ip>
    net show bgp [l2vpn] evpn route rd <rd> type (macip|multicast|prefix)
    net show bgp [l2vpn] evpn route type (macip|multicast|prefix)
    net show bgp [l2vpn] evpn route vni <1-16777215>
    net show bgp [l2vpn] evpn route vni <1-16777215> mac <mac>
    net show bgp [l2vpn] evpn route vni <1-16777215> mac <mac> ip <ip>
    net show bgp [l2vpn] evpn route vni <1-16777215> multicast <ipv4>
    net show bgp [l2vpn] evpn route vni <1-16777215> type (macip|multicast)
    net show bgp [l2vpn] evpn route vni <1-16777215> vtep <ipv4>
    net show bgp [l2vpn] evpn route vni all
    net show bgp [l2vpn] evpn route vni all vtep <ipv4>
    net show bgp [l2vpn] evpn summary [json]
    net show bgp [l2vpn] evpn vni [<1-16777215>]
    net show bgp [l2vpn] evpn vrf-import-rt [json]
    net show bgp [summary] [json]
    net show bgp ipv4 (unicast|labeled-unicast) [<ipv4>|<ipv4/prefixlen>|summary] [json]
    net show bgp ipv6 (unicast|labeled-unicast) [<ipv6>|<ipv6/prefixlen>|summary] [json]
    net show bgp neighbor <bgppeer> (advertised-routes|received-routes|routes) [json]
    net show bgp neighbor [<bgppeer>] [json]
    net show bgp update-groups
    net show bgp vni [json]
    net show bgp vrf <text> (<ipv4>|<ipv4/prefixlen>|<ipv6>|<ipv6/prefixlen>) [bestpath|multipath] [json]
    net show bgp vrf <text> (ipv4|ipv6) (unicast|labeled-unicast) neighbor <bgppeer> (advertised-routes|received-routes|routes) [json]
    net show bgp vrf <text> [summary] [json]
    net show bgp vrf <text> ipv4 unicast [<ipv4>|<ipv4/prefixlen>|summary] [json]
    net show bgp vrf <text> ipv6 unicast [<ipv6>|<ipv6/prefixlen>|summary] [json]
    net show bgp vrf <text> neighbor <bgppeer> (advertised-routes|received-routes|routes) [json]
    net show bgp vrf <text> neighbor [<bgppeer>] [json]
    net show bgp vrf <text> update-groups
    net show bgp vrf <text> vni [json]
    net show configuration bgp
    net show route [<ipv4>|<ipv4/prefixlen>|<ipv6>|<ipv6/prefixlen>|bgp|connected|json|kernel|ospf|ospf6|pim|rip|static|summary|supernets-only|table] [json]
    net show route vrf <text> [<ipv4>|<ipv4/prefixlen>|<ipv6>|<ipv6/prefixlen>|bgp|connected|json|kernel|ospf|ospf6|pim|rip|static|summary|supernets-only|table] [json]


```
## net show route ipv4
```

ERROR: Command not found

net show route ipv4
               ^ Invalid value here
Did you mean one of the following?

    net show route-map [94m[<route-map>][0m
        This command is looking for an existing route-map

```
```

The following commands contain keyword(s) 'show', 'route', 'ipv4'

    net show bgp (ipv4|ipv6) (unicast|labeled-unicast) neighbor <bgppeer> (advertised-routes|received-routes|routes) [json]
    net show bgp vrf <text> (ipv4|ipv6) (unicast|labeled-unicast) neighbor <bgppeer> (advertised-routes|received-routes|routes) [json]


```
## ip neighbor
```

192.168.0.21 dev eth1 lladdr 44:38:39:00:06:00 REACHABLE
192.168.0.34 dev eth1 lladdr 44:38:39:00:0b:00 REACHABLE
192.168.0.11 dev eth1 lladdr 44:38:39:00:02:00 REACHABLE
192.168.0.33 dev eth1 lladdr 44:38:39:00:0a:00 REACHABLE
192.168.0.14 dev eth1 lladdr 44:38:39:00:05:00 REACHABLE
192.168.0.31 dev eth1 lladdr 44:38:39:00:08:00 REACHABLE
169.254.0.1 dev eth3 lladdr 44:38:39:00:03:07 PERMANENT
192.168.0.32 dev eth1 lladdr 44:38:39:00:09:00 REACHABLE
192.168.0.13 dev eth1 lladdr 44:38:39:00:04:00 REACHABLE
192.168.0.12 dev eth1 lladdr 44:38:39:00:03:00 REACHABLE
169.254.0.1 dev eth2 lladdr 44:38:39:00:02:07 PERMANENT
192.168.0.22 dev eth1 lladdr 44:38:39:00:07:00 REACHABLE
10.255.0.3 dev eth0 lladdr 2c:c2:60:ff:00:4d REACHABLE
fe80::4638:39ff:fe00:307 dev eth3 lladdr 44:38:39:00:03:07 router REACHABLE
fe80::4638:39ff:fe00:207 dev eth2 lladdr 44:38:39:00:02:07 router REACHABLE

```
```

Command "--help" is unknown, try "ip neigh help".

192.168.0.21 dev eth1 lladdr 44:38:39:00:06:00 REACHABLE
192.168.0.34 dev eth1 lladdr 44:38:39:00:0b:00 REACHABLE
192.168.0.11 dev eth1 lladdr 44:38:39:00:02:00 REACHABLE
192.168.0.33 dev eth1 lladdr 44:38:39:00:0a:00 REACHABLE
192.168.0.14 dev eth1 lladdr 44:38:39:00:05:00 REACHABLE
192.168.0.31 dev eth1 lladdr 44:38:39:00:08:00 REACHABLE
169.254.0.1 dev eth3 lladdr 44:38:39:00:03:07 PERMANENT
192.168.0.32 dev eth1 lladdr 44:38:39:00:09:00 REACHABLE
192.168.0.13 dev eth1 lladdr 44:38:39:00:04:00 REACHABLE
192.168.0.12 dev eth1 lladdr 44:38:39:00:03:00 REACHABLE
169.254.0.1 dev eth2 lladdr 44:38:39:00:02:07 PERMANENT
192.168.0.22 dev eth1 lladdr 44:38:39:00:07:00 REACHABLE
10.255.0.3 dev eth0 lladdr 2c:c2:60:ff:00:4d REACHABLE
fe80::4638:39ff:fe00:307 dev eth3 lladdr 44:38:39:00:03:07 router REACHABLE
fe80::4638:39ff:fe00:207 dev eth2 lladdr 44:38:39:00:02:07 router REACHABLE

```
## net show bgp neighbor
```

BGP neighbor on eth2: fe80::4638:39ff:fe00:207, remote AS 65011, local AS 65041, external link
Hostname: leaf01
  BGP version 4, remote router ID 10.0.0.11
  BGP state = Established, up for 01:42:08
  Last read 00:00:01, Last write 00:00:01
  Hold time is 9, keepalive interval is 3 seconds
  Neighbor capabilities:
    4 Byte AS: advertised and received
    AddPath:
      IPv4 Unicast: RX advertised IPv4 Unicast and received
      IPv6 Unicast: RX advertised IPv6 Unicast and received
    Extended nexthop: advertised and received
      Address families by peer:
                   IPv4 Unicast
    Route refresh: advertised and received(old & new)
    Address Family IPv4 Unicast: advertised and received
    Address Family IPv6 Unicast: advertised and received
    Hostname Capability: advertised (name: oob-mgmt-server,domain name: n/a) received (name: leaf01,domain name: n/a)
    Graceful Restart Capabilty: advertised and received
      Remote Restart timer is 120 seconds
      Address families by peer:
        none
  Graceful restart informations:
    End-of-RIB send: IPv4 Unicast, IPv6 Unicast
    End-of-RIB received: IPv4 Unicast, IPv6 Unicast
  Message statistics:
    Inq depth is 0
    Outq depth is 0
                         Sent       Rcvd
    Opens:                  1          1
    Notifications:          0          0
    Updates:               30         29
    Keepalives:          2043       2043
    Route Refresh:          0          0
    Capability:             0          0
    Total:               2074       2073
  Minimum time between advertisement runs is 0 seconds

 For address family: IPv4 Unicast
  Update group 1, subgroup 1
  Packet Queue length 0
  Community attribute sent to this neighbor(all)
  14 accepted prefixes

 For address family: IPv6 Unicast
  Update group 2, subgroup 2
  Packet Queue length 0
  Community attribute sent to this neighbor(all)
  6 accepted prefixes

  Connections established 1; dropped 0
  Last reset never
Local host: fe80::4638:39ff:fe00:102, Local port: 55410
Foreign host: fe80::4638:39ff:fe00:207, Foreign port: 179
Nexthop: 10.0.0.41
Nexthop global: fe80::4638:39ff:fe00:102
Nexthop local: fe80::4638:39ff:fe00:102
BGP connection: shared network
BGP Connect Retry Timer in Seconds: 10
Estimated round trip time: 1 ms
Read thread: on  Write thread: on

BGP neighbor on eth3: fe80::4638:39ff:fe00:307, remote AS 65012, local AS 65041, external link
Hostname: leaf02
  BGP version 4, remote router ID 10.0.0.12
  BGP state = Established, up for 01:42:10
  Last read 00:00:03, Last write 00:00:03
  Hold time is 9, keepalive interval is 3 seconds
  Neighbor capabilities:
    4 Byte AS: advertised and received
    AddPath:
      IPv4 Unicast: RX advertised IPv4 Unicast and received
      IPv6 Unicast: RX advertised IPv6 Unicast and received
    Extended nexthop: advertised and received
      Address families by peer:
                   IPv4 Unicast
    Route refresh: advertised and received(old & new)
    Address Family IPv4 Unicast: advertised and received
    Address Family IPv6 Unicast: advertised and received
    Hostname Capability: advertised (name: oob-mgmt-server,domain name: n/a) received (name: leaf02,domain name: n/a)
    Graceful Restart Capabilty: advertised and received
      Remote Restart timer is 120 seconds
      Address families by peer:
        none
  Graceful restart informations:
    End-of-RIB send: IPv4 Unicast, IPv6 Unicast
    End-of-RIB received: IPv4 Unicast, IPv6 Unicast
  Message statistics:
    Inq depth is 0
    Outq depth is 0
                         Sent       Rcvd
    Opens:                  1          1
    Notifications:          0          0
    Updates:               32         31
    Keepalives:          2043       2043
    Route Refresh:          0          0
    Capability:             0          0
    Total:               2076       2075
  Minimum time between advertisement runs is 0 seconds

 For address family: IPv4 Unicast
  Update group 1, subgroup 1
  Packet Queue length 0
  Community attribute sent to this neighbor(all)
  14 accepted prefixes

 For address family: IPv6 Unicast
  Update group 2, subgroup 2
  Packet Queue length 0
  Community attribute sent to this neighbor(all)
  6 accepted prefixes

  Connections established 1; dropped 0
  Last reset never
Local host: fe80::4638:39ff:fe00:103, Local port: 60999
Foreign host: fe80::4638:39ff:fe00:307, Foreign port: 179
Nexthop: 10.0.0.41
Nexthop global: fe80::4638:39ff:fe00:103
Nexthop local: fe80::4638:39ff:fe00:103
BGP connection: shared network
BGP Connect Retry Timer in Seconds: 10
Estimated round trip time: 1 ms
Read thread: on  Write thread: on



```
```

The following commands contain keyword(s) 'show', 'bgp', 'neighbor'

    net show bgp (ipv4|ipv6) (unicast|labeled-unicast) neighbor <bgppeer> (advertised-routes|received-routes|routes) [json]
    net show bgp neighbor <bgppeer> (advertised-routes|received-routes|routes) [json]
    net show bgp neighbor [<bgppeer>] [json]
    net show bgp vrf <text> (ipv4|ipv6) (unicast|labeled-unicast) neighbor <bgppeer> (advertised-routes|received-routes|routes) [json]
    net show bgp vrf <text> neighbor <bgppeer> (advertised-routes|received-routes|routes) [json]
    net show bgp vrf <text> neighbor [<bgppeer>] [json]


```
## net show bgp 10.0.0.12
```

BGP routing table entry for 10.0.0.12/32
Paths: (2 available, best #2, table Default-IP-Routing-Table)
  Advertised to non peer-group peers:
  leaf01(eth2) leaf02(eth3)
  65011 65020 65012
    fe80::4638:39ff:fe00:207 from leaf01(eth2) (10.0.0.11)
    (fe80::4638:39ff:fe00:207) (used)
      Origin IGP, localpref 100, valid, external, bestpath-from-AS 65011
      AddPath ID: RX 0, TX 15
      Last update: Thu Jul 19 18:07:58 2018

  65012
    fe80::4638:39ff:fe00:307 from leaf02(eth3) (10.0.0.12)
    (fe80::4638:39ff:fe00:307) (used)
      Origin IGP, metric 0, localpref 100, valid, external, bestpath-from-AS 65012, best
      AddPath ID: RX 0, TX 7
      Last update: Thu Jul 19 18:07:55 2018


```
```

ERROR: There are no commands with keyword(s) 'show', 'bgp', '10.0.0.12'

```
## cat /etc/frr/frr.conf
```

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

```
## cat /etc/cumulus/acl/policy.d/01control_plane_bgp.rules
```

cat: /etc/cumulus/acl/policy.d/01control_plane_bgp.rules: No such file or directory

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

cat: /etc/cumulus/acl/policy.d/01control_plane_bgp.rules: No such file or directory

```
