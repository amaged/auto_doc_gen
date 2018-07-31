# CLAG
## netq check clag
```

No CLAG session info found

```
```

The following commands contain keyword(s) 'check', 'clag'

    netq check clag [json]
    netq check clag around <text-time> [json]
    netq example check clag


Unable to find command netq check clag --help

No CLAG session info found

```
## net example clag basic-clag
```


Scenario
========


            ---------------                   ---------------
           |               | swp3       swp3 |               |
           |    switch1    |=================|    switch2    |
           | mgmt=10.0.0.1 | swp4       swp4 | mgmt=10.0.0.2 |
            ---------------                   ---------------
                   | swp1                            | swp1
                   |            ---------            |
                   |           |         |           |
                    -----------| host-11 |-----------
                               |         |
                                ---------

We want to create an MLAG peering relationship between switch1 and switch2 on
their swp3 and swp4 interfaces, create vlans 100-200, and dual connect host-11 to
swp1 on both switch1 and switch2.

You will need to configure switch1 and switch2, the steps for both are
very similar.

- create the peering; select one switch to be primary and the other secondary
  - backup-ip is an optional (recommened) IP address that is separately reachable

- create VLANs 100-200

- configure a host facing interface for clag
  - switch1 and switch2 MUST use the same clag-id for host-11

- connect the clag to host-11 to vlan 100 untagged

- review and commit

net commands
============

switch1# net add clag peer sys-mac 44:38:39:FF:01:01 interface swp3-4 primary backup-ip 10.0.0.2
switch1# net add vlan 100-200
switch1# net add clag port bond bond-to-host-11 interface swp1 clag-id 1
switch1# net add bond bond-to-host-11 bridge access 100
switch1# net pending
switch1# net commit

switch2# net add clag peer sys-mac 44:38:39:FF:01:01 interface swp3-4 secondary backup-ip 10.0.0.1
switch2# net add vlan 100-200
switch2# net add clag port bond bond-to-host-11 interface swp1 clag-id 1
switch2# net add bond bond-to-host-11 bridge access 100
switch2# net pending
switch2# net commit

Verification
============
switch1# net show interface
switch1# net show clag

```
```

The following commands contain keyword(s) 'example', 'clag', 'basic-clag'

    net example clag basic-clag


```
## net show clag
```



```
```

The following commands contain keyword(s) 'show', 'clag'

    net show clag [our-macs|our-multicast-entries|our-multicast-router-ports|peer-macs|peer-multicast-entries|peer-multicast-router-ports|params|backup-ip|id] [verbose] [json]
    net show clag macs [<mac>] [json]
    net show clag peer-lacp-rate
    net show clag status [verbose] [json]
    net show clag verify-vlans [verbose]


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
## net show bridge link %DP
```

ERROR: Command not found

net show bridge link %DP
                     ^ Invalid value here
Use 'net help KEYWORD(s)' to list all options that use KEYWORD(s)

```
```

ERROR: There are no commands with keyword(s) 'show', 'bridge', 'link', '%DP'

```
## net show clag backup-ip
```



```
```

The following commands contain keyword(s) 'show', 'clag', 'backup-ip'

    net show clag [our-macs|our-multicast-entries|our-multicast-router-ports|peer-macs|peer-multicast-entries|peer-multicast-router-ports|params|backup-ip|id] [verbose] [json]


```
## net show configuration
```


interface lo
  address 10.0.0.41/32
  address fd00::41/128

interface eth0
  address 10.255.0.1
  gateway 10.255.0.3
  netmask 255.255.0.0

interface eth1
  address 192.168.0.254
  netmask 255.255.0.0

interface eth2
  ipv6 nd ra-interval 10
  no ipv6 nd suppress-ra

interface eth3
  ipv6 nd ra-interval 10
  no ipv6 nd suppress-ra

hostname oob-mgmt-server

frr version 3.2+cl3u4

frr defaults datacenter

username cumulus nopassword

service integrated-vtysh-config

log syslog informational

router bgp 65041
  bgp router-id 10.0.0.41
  coalesce-time 1000
  bgp bestpath as-path multipath-relax
  neighbor eth2 interface remote-as external
  neighbor eth3 interface remote-as external
  
  address-family ipv4 unicast
    network 10.0.0.41/32 
    network 10.0.2.0/24 
  
  address-family ipv6 unicast
    network fd00::41/128 
    neighbor eth2 activate
    neighbor eth3 activate

line vty

dot1x
  mab-activation-delay 30
  eap-reauth-period 0
  
  radius
    accounting-port 1813
    authentication-port 1812

time
  
  zone
    Etc/UTC
  
  ntp
    
    servers
      0.cumulusnetworks.pool.ntp.org iburst
      1.cumulusnetworks.pool.ntp.org iburst
      2.cumulusnetworks.pool.ntp.org iburst
      3.cumulusnetworks.pool.ntp.org iburst
    
    source
      eth0

dns
  
  nameserver
    8.8.8.8

snmp-server
  listening-address localhost

```
```

The following commands contain keyword(s) 'show', 'configuration'

    net show configuration
    net show configuration acl
    net show configuration bgp
    net show configuration commands
    net show configuration dhcp [json]
    net show configuration dns
    net show configuration dot1x
    net show configuration files
    net show configuration interface <interface>
    net show configuration multicast
    net show configuration ospf
    net show configuration ospf6
    net show configuration snmp-server
    net show configuration syslog


```
## net show clag status verbose
```



```
```

The following commands contain keyword(s) 'show', 'clag', 'status', 'verbose'

    net show clag status [verbose] [json]


```
## sudo cl-service-summary summary
```

Service cron         enabled    active   
Service sshd         enabled    active   
Service syslog       enabled    active   
Service asic-monitor enabled    inactive 
Service clagd        disabled   inactive 
Service cumulus-poe             inactive 
Service lldpd        enabled    active   
Service mstpd        disabled   inactive 
Service neighmgrd    enabled    active   
Service netd         enabled    active   
Service netq-agent   enabled    active   
Service portwd       enabled    active   
Service ptmd         enabled    active   
Service pwmd         enabled    active   
Service smond        enabled    active   
Service switchd      enabled    active   
Service sysmonitor   enabled    active   
Service vxrd         disabled   inactive 
Service vxsnd        disabled   inactive 
Service rdnbrd       disabled   inactive 
Service frr          enabled    active   
Service bgpd         enabled    active   
Service eigrpd       disabled   inactive 
Service isisd        disabled   inactive 
Service ldpd         disabled   inactive 
Service nhrpd        disabled   inactive 
Service ospf6d       disabled   inactive 
Service ospfd        disabled   inactive 
Service pimd         disabled   inactive 
Service ripd         disabled   inactive 
Service ripngd       disabled   inactive 
Service zebra        enabled    active   

```
```

Service cron         enabled    active   
Service sshd         enabled    active   
Service syslog       enabled    active   
Service asic-monitor enabled    inactive 
Service clagd        disabled   inactive 
Service cumulus-poe             inactive 
Service lldpd        enabled    active   
Service mstpd        disabled   inactive 
Service neighmgrd    enabled    active   
Service netd         enabled    active   
Service netq-agent   enabled    active   
Service portwd       enabled    active   
Service ptmd         enabled    active   
Service pwmd         enabled    active   
Service smond        enabled    active   
Service switchd      enabled    active   
Service sysmonitor   enabled    active   
Service vxrd         disabled   inactive 
Service vxsnd        disabled   inactive 
Service rdnbrd       disabled   inactive 
Service frr          enabled    active   
Service bgpd         enabled    active   
Service eigrpd       disabled   inactive 
Service isisd        disabled   inactive 
Service ldpd         disabled   inactive 
Service nhrpd        disabled   inactive 
Service ospf6d       disabled   inactive 
Service ospfd        disabled   inactive 
Service pimd         disabled   inactive 
Service ripd         disabled   inactive 
Service ripngd       disabled   inactive 
Service zebra        enabled    active   

```
## sudo systemctl status clagd.service
```

● clagd.service - Cumulus Linux Multi-Chassis LACP Bonding Daemon
   Loaded: loaded (/lib/systemd/system/clagd.service; disabled)
   Active: inactive (dead)
     Docs: man:clagd(8)

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
## net show bridge spanning-tree
```


WARNING: '/sbin/mstpctl showbridge bridge' failed due to:
Command '['/sbin/mstpctl', 'showbridge', 'bridge']' returned non-zero exit status 1


WARNING: '/sbin/mstpctl showport bridge' failed due to:
Command '['/sbin/mstpctl', 'showport', 'bridge']' returned non-zero exit status 1

```
```

The following commands contain keyword(s) 'show', 'bridge', 'spanning-tree'

    net show bridge spanning-tree [<interface>] [json]
    net show bridge spanning-tree detail [json]


```
## net show counters
```


Kernel Interface table
Iface      MTU    Met    RX_OK    RX_ERR    RX_DRP    RX_OVR    TX_OK    TX_ERR    TX_DRP    TX_OVR  Flg
-------  -----  -----  -------  --------  --------  --------  -------  --------  --------  --------  -----
docker0   1500      0        0         0         0         0        0         0         0         0  BMU
eth0      1500      0    22628         0         0         0    22702         0         0         0  BMRU
eth1      1500      0    63404         0         0         0    51713         0         0         0  BMRU
eth2      1500      0     4043         0         2         0     4241         0         0         0  BMRU
eth3      1500      0     4170         0         1         0     3973         0         0         0  BMRU
lo       65536      0    22210         0         0         0    22210         0         0         0  LRU


```
```

The following commands contain keyword(s) 'show', 'counters'

    net show counters [json]


```
## sudo ethtool -S %DP
```

Cannot get stats strings information: No such device

```
```

ethtool: bad command line argument(s)
For more information run ethtool -h

```
## net show interface bond1
```

       Name    MAC    Speed    MTU    Mode
-----  ------  -----  -------  -----  -------------
ADMDN  bond1          N/A             NotConfigured

Counters      TX    RX
----------  ----  ----
unicast        0     0
broadcast      0     0
multicast      0     0
errors         0     0

Routing
-------
  % Can't find interface bond1

```
```

ERROR: There are no commands with keyword(s) 'show', 'interface', 'bond1'

```
## clagctl
```

Unable to communicate with clagd. Is it running?

```
```

usage: clagctl [-h] [-j] [-v] [command [args]]

CLAG daemon control interface, version 0.1.0

positional arguments:
  command        Command to execute, default is 'status'
  args           Additional command parameters

optional arguments:
  -h, --help     show this help message and exit
  -v, --verbose  Increase the amount of output.
  -j, --json     json output.

The commands are:
cleardebugflags       Removes or clears the debug logging flags
collectgarbage        Causes clagd to run python's garbage collection
connstate             Display socket connection state with peer
debug                 Sets the debugging level
dumpourmacs           Displays the MACs learned on this switch
dumpourmcast          Displays the multicast entries learned on this switch
dumpourrport          Displays the multicast router ports learned on this switch
dumppeermacs          Displays the MACs learned on the peer switch
dumppeermcast         Displays the multicast entries learned on the peer switch
dumppeerrport         Displays the multicast router ports learned on the peer switch
echo                  Echo back the supplied string
lacppoll              The frequency clagd collects information and sends to peer
logfile               Sets the name of the log file
logmsg                Outputs a message to the log file
params                Display the parameters in use by clagd
peerlacprate          Displays the peer's polling rate
peerlinkpoll          The frequency clagd polls the status of the peer interface
peertimeout           The time clagd expects a message from the peer
priority              Sets the priority of clagd
quiet                 Prevents output in the log file
reloaddone            Config reload done
sendbufsize           The size of the socket send buffer, in bytes
sendtimeout           The time clagd send socket waits to enqueue data
setanycastip          Sets the VXLAN anycast IP address
setbackupip           Sets the backup IP address
setclagid             Associates a bond with a clag id
setdebugflags         Sets the debug logging flags
showbackupip          Displays backup link info
showclagid            Displays the CLAG bonds configured on this switch
showdebugflags        Shows the debug logging flags
status                Display the status of the clagd daemon
verbose               Enables additional output in log file
verifyvlans           Verifies VLAN configuration with the peer

See the clagctl man page for more information

```
