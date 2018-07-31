# VRF : In Cumulus Linux, the following services work with VRF instances:
## vrf list
```


VRF              Table
---------------- -----


```
```

vrf <OPTS>

VRF domains:
    vrf list

Links associated with VRF domains:
    vrf link list [<vrf-name>]

Routes for a VRF domain:
    vrf route list [<vrf-name>]

Tasks and VRF domain asociation:
    vrf task exec <vrf-name> <command>
    vrf task list [<vrf-name>]
    vrf task identify <pid>

    NOTE: This command affects only AF_INET and AF_INET6 sockets opened by the
          command that gets exec'ed. Specifically, it has *no* impact on netlink
          sockets (e.g., ip command).

```
## vrf task list rocket
```


VRF: rocket          
-----------------------
No cgroup for vrf


```
```


VRF: rocket          
-----------------------
No cgroup for vrf

VRF: --help          
-----------------------
No cgroup for vrf



VRF: rocket          
-----------------------
No cgroup for vrf


```
## vrf task identify 2829
```

Process does not exist.

```
```

Process does not exist.

```
## sudo vrf task exec rocket ssh user@host
```

ERROR: VRF does not exist

```
```

ERROR: VRF does not exist

```
## net show bgp vrf turtle ipv4 unicast route-leak
```

ERROR: Command not found

net show bgp vrf turtle ipv4 unicast route-leak
                                     ^ Invalid value here
Use 'net help KEYWORD(s)' to list all options that use KEYWORD(s)

```
```

ERROR: There are no commands with keyword(s) 'show', 'bgp', 'vrf', 'turtle', 'ipv4', 'unicast', 'route-leak'

```
## net show route vrf turtle ipv4
```

ERROR: Command not found

net show route vrf turtle ipv4
                          ^ Invalid value here
Use 'net help KEYWORD(s)' to list all options that use KEYWORD(s)

```
```

ERROR: There are no commands with keyword(s) 'show', 'route', 'vrf', 'turtle', 'ipv4'

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
## net show bgp vrf rocket summary
```


show bgp vrf rocket ipv4 unicast summary
========================================
% No such BGP instance exist


show bgp vrf rocket ipv6 unicast summary
========================================
% No such BGP instance exist

```
```

ERROR: There are no commands with keyword(s) 'show', 'bgp', 'vrf', 'rocket', 'summary'

```
## net show bgp vrf vrf1012
```


show bgp vrf vrf1012 ipv4 unicast
=================================
View/Vrf specified is unknown: vrf1012


show bgp vrf vrf1012 ipv6 unicast
=================================
View/Vrf specified is unknown: vrf1012

```
```

ERROR: There are no commands with keyword(s) 'show', 'bgp', 'vrf', 'vrf1012'

```
## net show ospf vrf all
```

ospfd is not running

```
```

The following commands contain keyword(s) 'show', 'ospf', 'vrf', 'all'

    net show ospf vrf <text> neighbor [all|<interface>|<ipv4>|detail] [json]


```
## net show ospf vrf vrf1012 route
```

ospfd is not running

```
```

ERROR: There are no commands with keyword(s) 'show', 'ospf', 'vrf', 'vrf1012', 'route'

```
## ip -d link show type vrf
```


```
```

Device "--help" does not exist.


```
## ip -d link show vrf vrf1012
```

Error: argument "vrf1012" is wrong: Not a valid VRF name


```
```

Error: argument "vrf1012" is wrong: Not a valid VRF name


```
## ip route show table vrf1012
```

Error: argument "vrf1012" is wrong: table id value is invalid


```
```

Error: argument "vrf1012" is wrong: table id value is invalid


```
## ip -6 route show table vrf1012
```

Error: argument "vrf1012" is wrong: table id value is invalid


```
```

Error: argument "vrf1012" is wrong: table id value is invalid


```
## ip link list rocket
```

Device "rocket" does not exist.

```
```

Error: either "dev" is duplicate, or "--help" is a garbage.

Device "rocket" does not exist.

```
## net show mroute vrf blue
```

pimd is not running

```
```

ERROR: There are no commands with keyword(s) 'show', 'mroute', 'vrf', 'blue'

```
## sudo systemctl status dhcrelay@rocket.service
```

● dhcrelay@rocket.service - DHCPv4 Relay Agent Daemon rocket
   Loaded: loaded (/lib/systemd/system/dhcrelay@.service; disabled)
  Drop-In: /run/systemd/generator/dhcrelay@.service.d
           └─vrf.conf
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
## sudo vrf task exec rocket /usr/sbin/dhcrelay -d -q -i %DP -i %DP 102.0.0.2
```

ERROR: VRF does not exist

```
```

ERROR: VRF does not exist

```
## ping -I turtle
```

Usage: ping [-aAbBdDfhLnOqrRUvV] [-c count] [-i interval] [-I interface]
            [-m mark] [-M pmtudisc_option] [-l preload] [-p pattern] [-Q tos]
            [-s packetsize] [-S sndbuf] [-t ttl] [-T timestamp_option]
            [-w deadline] [-W timeout] [hop1 ...] destination

```
```

ping: invalid option -- '-'
Usage: ping [-aAbBdDfhLnOqrRUvV] [-c count] [-i interval] [-I interface]
            [-m mark] [-M pmtudisc_option] [-l preload] [-p pattern] [-Q tos]
            [-s packetsize] [-S sndbuf] [-t ttl] [-T timestamp_option]
            [-w deadline] [-W timeout] [hop1 ...] destination

Usage: ping [-aAbBdDfhLnOqrRUvV] [-c count] [-i interval] [-I interface]
            [-m mark] [-M pmtudisc_option] [-l preload] [-p pattern] [-Q tos]
            [-s packetsize] [-S sndbuf] [-t ttl] [-T timestamp_option]
            [-w deadline] [-W timeout] [hop1 ...] destination

```
## sudo traceroute -i turtle
```

Specify "host" missing argument.

```
```

Usage:
  traceroute [ -46dFITnreAUDV ] [ -f first_ttl ] [ -g gate,... ] [ -i device ] [ -m max_ttl ] [ -N squeries ] [ -p port ] [ -t tos ] [ -l flow_label ] [ -w waittime ] [ -q nqueries ] [ -s src_addr ] [ -z sendwait ] [ --fwmark=num ] host [ packetlen ]
Options:
  -4                          Use IPv4
  -6                          Use IPv6
  -d  --debug                 Enable socket level debugging
  -F  --dont-fragment         Do not fragment packets
  -f first_ttl  --first=first_ttl
                              Start from the first_ttl hop (instead from 1)
  -g gate,...  --gateway=gate,...
                              Route packets through the specified gateway
                              (maximum 8 for IPv4 and 127 for IPv6)
  -I  --icmp                  Use ICMP ECHO for tracerouting
  -T  --tcp                   Use TCP SYN for tracerouting (default port is 80)
  -i device  --interface=device
                              Specify a network interface to operate with
  -m max_ttl  --max-hops=max_ttl
                              Set the max number of hops (max TTL to be
                              reached). Default is 30
  -N squeries  --sim-queries=squeries
                              Set the number of probes to be tried
                              simultaneously (default is 16)
  -n                          Do not resolve IP addresses to their domain names
  -p port  --port=port        Set the destination port to use. It is either
                              initial udp port value for "default" method
                              (incremented by each probe, default is 33434), or
                              initial seq for "icmp" (incremented as well,
                              default from 1), or some constant destination
                              port for other methods (with default of 80 for
                              "tcp", 53 for "udp", etc.)
  -t tos  --tos=tos           Set the TOS (IPv4 type of service) or TC (IPv6
                              traffic class) value for outgoing packets
  -l flow_label  --flowlabel=flow_label
                              Use specified flow_label for IPv6 packets
  -w waittime  --wait=waittime
                              Set the number of seconds to wait for response to
                              a probe (default is 5.0). Non-integer (float
                              point) values allowed too
  -q nqueries  --queries=nqueries
                              Set the number of probes per each hop. Default is
                              3
  -r                          Bypass the normal routing and send directly to a
                              host on an attached network
  -s src_addr  --source=src_addr
                              Use source src_addr for outgoing packets
  -z sendwait  --sendwait=sendwait
                              Minimal time interval between probes (default 0).
                              If the value is more than 10, then it specifies a
                              number in milliseconds, else it is a number of
                              seconds (float point values allowed too)
  -e  --extensions            Show ICMP extensions (if present), including MPLS
  -A  --as-path-lookups       Perform AS path lookups in routing registries and
                              print results directly after the corresponding
                              addresses
  -M name  --module=name      Use specified module (either builtin or external)
                              for traceroute operations. Most methods have
                              their shortcuts (`-I' means `-M icmp' etc.)
  -O OPTS,...  --options=OPTS,...
                              Use module-specific option OPTS for the
                              traceroute module. Several OPTS allowed,
                              separated by comma. If OPTS is "help", print info
                              about available options
  --sport=num                 Use source port num for outgoing packets. Implies
                              `-N 1'
  --fwmark=num                Set firewall mark for outgoing packets
  -U  --udp                   Use UDP to particular port for tracerouting
                              (instead of increasing the port per each probe),
                              default port is 53
  -UL                         Use UDPLITE for tracerouting (default dest port
                              is 53)
  -D  --dccp                  Use DCCP Request for tracerouting (default port
                              is 33434)
  -P prot  --protocol=prot    Use raw packet of protocol prot for tracerouting
  --mtu                       Discover MTU along the path being traced. Implies
                              `-F -N 1'
  --back                      Guess the number of hops in the backward path and
                              print if it differs
  -V  --version               Print version info and exit
  --help                      Read this help and exit

Arguments:
+     host          The host to traceroute to
      packetlen     The full packet length (default is the length of an IP
                    header plus 40). Can be ignored or increased to a minimal
                    allowed value

Specify "host" missing argument.

```
