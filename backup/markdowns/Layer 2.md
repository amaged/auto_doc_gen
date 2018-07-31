# Layer 2
## sudo ifquery --check bond0
```

error: cannot find interfaces: bond0

```
```

usage: ifquery [-h] [-a] [-v] [-d] [--allow CLASS] [-w] [-X EXCLUDEPATS]
               [-i INTERFACESFILE] [-t {native,json}] [-T {iface,vlan}] [-l]
               [-r | -c | -x] [-o {native,json}] [-p {list,dot}] [-s]
               [--with-defaults] [-V]
               [IFACE [IFACE ...]]

query interfaces (all or interface list)

positional arguments:
  IFACE                 interface list separated by spaces. IFACE list is
                        mutually exclusive with -a option.

optional arguments:
  -h, --help            show this help message and exit
  -a, --all             process all interfaces marked "auto"
  -v, --verbose         verbose
  -d, --debug           output debug info
  --allow CLASS         ignore non-"allow-CLASS" interfaces
  -w, --with-depends    run with all dependent interfaces. This option is
                        redundant when '-a' is specified. With '-a' interfaces
                        are always executed in dependency order
  -X EXCLUDEPATS, --exclude EXCLUDEPATS
                        Exclude interfaces from the list of interfaces to
                        operate on. Can be specified multiple times.
  -i INTERFACESFILE, --interfaces INTERFACESFILE
                        Specify interfaces file instead of file defined in
                        ifupdown2.conf file
  -t {native,json}, --interfaces-format {native,json}
                        interfaces file format
  -T {iface,vlan}, --type {iface,vlan}
                        type of interface entry (iface or vlan). This option
                        can be used in case of ambiguity between a vlan
                        interface and an iface interface of the same name
  -l, --list            list all matching known interfaces
  -r, --running         query running state of an interface
  -c, --check           check interface file contents against running state of
                        an interface
  -x, --raw             print raw config file entries
  -o {native,json}, --format {native,json}
                        interface display format
  -p {list,dot}, --print-dependency {list,dot}
                        print interface dependency
  -s, --syntax-help     print supported interface config syntax
  --with-defaults       check policy default file contents, for unconfigured
                        attributes, against running state of an interface
  -V, --version

```
## arp -n
```

Address                  HWtype  HWaddress           Flags Mask            Iface
192.168.0.21             ether   44:38:39:00:06:00   C                     eth1
192.168.0.34             ether   44:38:39:00:0b:00   C                     eth1
192.168.0.11             ether   44:38:39:00:02:00   C                     eth1
192.168.0.33             ether   44:38:39:00:0a:00   C                     eth1
192.168.0.14             ether   44:38:39:00:05:00   C                     eth1
192.168.0.31             ether   44:38:39:00:08:00   C                     eth1
169.254.0.1              ether   44:38:39:00:03:07   CM                    eth3
192.168.0.32             ether   44:38:39:00:09:00   C                     eth1
192.168.0.13             ether   44:38:39:00:04:00   C                     eth1
192.168.0.12             ether   44:38:39:00:03:00   C                     eth1
169.254.0.1              ether   44:38:39:00:02:07   CM                    eth2
192.168.0.22             ether   44:38:39:00:07:00   C                     eth1
10.255.0.3               ether   2c:c2:60:ff:00:4d   C                     eth0

```
```

nohup: failed to run command ‘arp’: No such file or directory

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
## cat /proc/net/bonding/bond0
```

cat: /proc/net/bonding/bond0: No such file or directory

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

cat: /proc/net/bonding/bond0: No such file or directory

```
## cl-netstat
```


Kernel Interface table
Iface      MTU    Met    RX_OK    RX_ERR    RX_DRP    RX_OVR    TX_OK    TX_ERR    TX_DRP    TX_OVR  Flg
-------  -----  -----  -------  --------  --------  --------  -------  --------  --------  --------  -----
docker0   1500      0        0         0         0         0        0         0         0         0  BMU
eth0      1500      0    22518         0         0         0    22592         0         0         0  BMRU
eth1      1500      0    63107         0         0         0    51503         0         0         0  BMRU
eth2      1500      0     4017         0         2         0     4222         0         0         0  BMRU
eth3      1500      0     4156         0         1         0     3949         0         0         0  BMRU
lo       65536      0    19799         0         0         0    19799         0         0         0  LRU


```
```

nohup: failed to run command ‘cl-netstat’: No such file or directory

```
## ethtool %DP
```

Cannot get device settings: No such device
Cannot get wake-on-lan settings: No such device
Cannot get message level: No such device
Cannot get link status: No such device
Settings for %DP:
No data available

```
```

nohup: failed to run command ‘ethtool’: No such file or directory

```
## ethtool -S %DP
```

Cannot get stats strings information: No such device

```
```

nohup: failed to run command ‘ethtool’: No such file or directory

```
## ifquery %DP
```

error: cannot find interfaces: %DP

```
```

nohup: failed to run command ‘ifquery’: No such file or directory

```
## ifreload -a
```


```
```

nohup: failed to run command ‘ifreload’: No such file or directory

```
## ifdown %DP ip addr show
```

error: cannot find interfaces: %DP ip addr show (interface was probably never up ?)

```
```

nohup: failed to run command ‘ifdown’: No such file or directory

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
## ip -s link
```

1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN mode DEFAULT group default 
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    RX: bytes  packets  errors  dropped overrun mcast   
    3951752    19802    0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    3951752    19802    0       0       0       0       
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:00 brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    11665477   22519    0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    3657460    22593    0       0       0       0       
3: eth1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:01 brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    7473954    63110    0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    23482294   51504    0       0       0       0       
4: eth2: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:02 brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    413755     4019     0       2       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    432978     4223     0       0       0       0       
5: eth3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:03 brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    425898     4156     0       1       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    409601     3949     0       0       0       0       
6: docker0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc noqueue state DOWN mode DEFAULT group default 
    link/ether 02:42:0d:8c:08:22 brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    0          0        0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    0          0        0       0       0       0       

```
```

Command "--help" is unknown, try "ip link help".

1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN mode DEFAULT group default 
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    RX: bytes  packets  errors  dropped overrun mcast   
    3951752    19802    0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    3951752    19802    0       0       0       0       
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:00 brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    11665477   22519    0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    3657460    22593    0       0       0       0       
3: eth1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:01 brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    7473954    63110    0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    23482294   51504    0       0       0       0       
4: eth2: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:02 brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    413755     4019     0       2       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    432978     4223     0       0       0       0       
5: eth3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP mode DEFAULT group default qlen 1000
    link/ether 44:38:39:00:01:03 brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    425898     4156     0       1       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    409601     3949     0       0       0       0       
6: docker0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc noqueue state DOWN mode DEFAULT group default 
    link/ether 02:42:0d:8c:08:22 brd ff:ff:ff:ff:ff:ff
    RX: bytes  packets  errors  dropped overrun mcast   
    0          0        0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    0          0        0       0       0       0       

```
## ip -br link show
```

lo               UNKNOWN        00:00:00:00:00:00 <LOOPBACK,UP,LOWER_UP> 
eth0             UP             44:38:39:00:01:00 <BROADCAST,MULTICAST,UP,LOWER_UP> 
eth1             UP             44:38:39:00:01:01 <BROADCAST,MULTICAST,UP,LOWER_UP> 
eth2             UP             44:38:39:00:01:02 <BROADCAST,MULTICAST,UP,LOWER_UP> 
eth3             UP             44:38:39:00:01:03 <BROADCAST,MULTICAST,UP,LOWER_UP> 
docker0          DOWN           02:42:0d:8c:08:22 <NO-CARRIER,BROADCAST,MULTICAST,UP> 

```
```

Device "--help" does not exist.

lo               UNKNOWN        00:00:00:00:00:00 <LOOPBACK,UP,LOWER_UP> 
eth0             UP             44:38:39:00:01:00 <BROADCAST,MULTICAST,UP,LOWER_UP> 
eth1             UP             44:38:39:00:01:01 <BROADCAST,MULTICAST,UP,LOWER_UP> 
eth2             UP             44:38:39:00:01:02 <BROADCAST,MULTICAST,UP,LOWER_UP> 
eth3             UP             44:38:39:00:01:03 <BROADCAST,MULTICAST,UP,LOWER_UP> 
docker0          DOWN           02:42:0d:8c:08:22 <NO-CARRIER,BROADCAST,MULTICAST,UP> 

```
## lldpcli snetstat -i
```

lldpcli: invalid option -- 'i'
Usage:   lldpcli [OPTIONS ...] [COMMAND ...]
Version: lldpd 2017-11-29

-d          Enable more debugging information.
-u socket   Specify the Unix-domain socket used for communication with lldpd(8).
-f format   Choose output format (plain, keyvalue, json, xml).
-c conf     Read the provided configuration file.

see manual page lldpcli(8) for more information

```
```

nohup: failed to run command ‘lldpcli’: No such file or directory

```
## brctl showmacs %B
```

read of forward table failed: No such device

```
```

nohup: failed to run command ‘brctl’: No such file or directory

```
## brctl showstp %B
```

%B: can't get info No such device

```
```

nohup: failed to run command ‘brctl’: No such file or directory

```
## bridge fdb show
```

02:42:0d:8c:08:22 dev docker0 master docker0 permanent

```
```

nohup: failed to run command ‘bridge’: No such file or directory

```
## bridge vlan show
```

port	vlan ids
docker0	None

```
```

nohup: failed to run command ‘bridge’: No such file or directory

```
## clagctl -v
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
## net show counters
```


Kernel Interface table
Iface      MTU    Met    RX_OK    RX_ERR    RX_DRP    RX_OVR    TX_OK    TX_ERR    TX_DRP    TX_OVR  Flg
-------  -----  -----  -------  --------  --------  --------  -------  --------  --------  --------  -----
docker0   1500      0        0         0         0         0        0         0         0         0  BMU
eth0      1500      0    22519         0         0         0    22593         0         0         0  BMRU
eth1      1500      0    63110         0         0         0    51504         0         0         0  BMRU
eth2      1500      0     4019         0         2         0     4223         0         0         0  BMRU
eth3      1500      0     4157         0         1         0     3951         0         0         0  BMRU
lo       65536      0    19802         0         0         0    19802         0         0         0  LRU


```
```

The following commands contain keyword(s) 'show', 'counters'

    net show counters [json]


```
## net show lldp
```


LocalPort    Speed    Mode    RemotePort    RemoteHost    Summary
-----------  -------  ------  ------------  ------------  ---------
eth2         1G       Mgmt    swp44         leaf01
eth3         1G       Mgmt    swp44         leaf02

```
```

The following commands contain keyword(s) 'show', 'lldp'

    net show lldp [<interface>] [json]
    net show lldp [json]


```
## net show interface
```

    Name     Master    Speed    MTU    Mode       Remote Host    Remote Port    Summary
--  -------  --------  -------  -----  ---------  -------------  -------------  --------------------------------------------
UP  lo                 N/A      65536  Loopback                                 IP: 127.0.0.1/8, 10.0.0.41/32, fd00::41/128,
                                                                                ::1/128
UP  eth0               1G       1500   Mgmt                                     IP: 10.255.0.1/16
UP  eth1               1G       1500   Mgmt                                     IP: 192.168.0.254/16
UP  eth2               1G       1500   Mgmt       leaf01         swp44
UP  eth3               1G       1500   Mgmt       leaf02         swp44
DN  docker0            N/A      1500   Bridge/L3                                IP: 172.17.0.1/16


```
```

The following commands contain keyword(s) 'show', 'interface'

    net show configuration interface <interface>
    net show dot1x interface <interface> [json]
    net show dot1x interface <interface> details [json]
    net show dot1x interface summary [json]
    net show igmp interface [detail|<interface>] [json]
    net show igmp vrf <text> interface [detail|<interface>] [json]
    net show interface (all|bonds|bondmems) [mac|json]
    net show interface <interface> detail
    net show interface [<interface>] [json]
    net show interface pluggables [json]
    net show mpls ldp (binding|discovery|interface|neighbor)
    net show mpls ldp (ipv4|ipv6) (binding|discovery|interface)
    net show ospf interface [<interface>] [json]
    net show ospf interface traffic [<interface>] [json]
    net show ospf vrf <text> interface [<interface>] [json]
    net show ospf vrf <text> interface traffic [<interface>] [json]
    net show ospf6 interface [<interface>]
    net show pim interface [detail|<interface>] [json]
    net show pim interface traffic [<interface>] [json]
    net show pim vrf <text> interface [detail|<interface>] [json]
    net show pim vrf <text> interface traffic [<interface>] [json]


```
