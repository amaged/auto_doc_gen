# VLANs
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
## sudo mstpctl showbridge %B100
```

can't setup control connection
ctl_client_init: Couldn't connect to server

```
```

Usage: mstpctl [commands]
commands:
	addbridge             <bridge> [<bridge> ...]              Add bridges to the mstpd's list
	delbridge             <bridge> [<bridge> ...]              Remove bridges from the mstpd's list
	showbridge            [json] [<bridge> ... [param]]        Show bridge state for the CIST
	showmstilist          <bridge>                             Show list of registered MSTIs
	showmstconfid         <bridge>                             Show MST ConfigId
	showvid2fid           <bridge>                             Show VID-to-FID allocation table
	showfid2mstid         <bridge>                             Show FID-to-MSTID allocation table
	showport              <bridge> [json] [<port> ... [param]] Show port state for the CIST
	showportdetail        <bridge> [json] [<port> ... [param]] Show port detailed state for the CIST
	showtree              <bridge> <mstid>                     Show bridge state for the given MSTI
	showtreeport          <bridge> <port> <mstid>              Show port detailed state for the given MSTI
	setmstconfid          <bridge> <revision> <name>           Set MST ConfigId elements: Revision Level (0-65535) and Name
	setvid2fid            <bridge> <FID>:<VIDs List>           Set VIDs-to-FIDs allocation
	setfid2mstid          <bridge> <mstid>:<FIDs List>         Set FIDs-to-MSTIDs allocation
	setmaxage             <bridge> <max_age>                   Set bridge max age (6-40)
	setfdelay             <bridge> <fwd_delay>                 Set bridge forward delay (4-30)
	setmaxhops            <bridge> <max_hops>                  Set bridge max hops (6-40)
	setforcevers          <bridge> {mstp|rstp|stp}             Force Spanning Tree protocol version
	settxholdcount        <bridge> <tx_hold_count>             Set bridge transmit hold count (1-10)
	createtree            <bridge> <mstid>                     Create new MSTI
	deletetree            <bridge> <mstid>                     Delete existing MSTI
	settreeprio           <bridge> <mstid> <priority>          Set bridge priority (0-65535) for the given MSTI
	setportpathcost       <bridge> <port> <cost>               Set port external path cost for the CIST (0 = auto)
	setportadminedge      <bridge> <port> {yes|no}             Set initial edge state
	setportautoedge       <bridge> <port> {yes|no}             Enable auto transition to/from edge state
	setportp2p            <bridge> <port> {yes|no|auto}        Set p2p detection mode
	setportrestrrole      <bridge> <port> {yes|no}             Restrict port ability to take Root role
	setportrestrtcn       <bridge> <port> {yes|no}             Restrict port ability to propagate received TCNs
	portmcheck            <bridge> <port>                      Try to get back from STP to rapid (RSTP/MSTP) mode
	setbpduguard          <bridge> <port> {yes|no}             Set bpdu guard state
	settreeportprio       <bridge> <port> <mstid> <priority>   Set port priority (0-240) for the given MSTI
	settreeportcost       <bridge> <port> <mstid> <cost>       Set port internal path cost for the given MSTI (0 = auto)
	showall               [json]                               Show detailed mstpctl info
	sethello              <bridge> <hello_time>                Set bridge hello time (1-10)
	setageing             <bridge> <ageing_time>               Set bridge ageing time (10-1000000)
	setportnetwork        <bridge> <port> {yes|no}             Set port network state
	setportbpdufilter     <bridge> <port> {yes|no}             Set BPDU filter state
	debuglevel            <level>                              Level of verbosity (1-4)

```
## sudo mstpctl showportde
```

can't setup control connection
ctl_client_init: Couldn't connect to server

```
```

Usage: mstpctl [commands]
commands:
	addbridge             <bridge> [<bridge> ...]              Add bridges to the mstpd's list
	delbridge             <bridge> [<bridge> ...]              Remove bridges from the mstpd's list
	showbridge            [json] [<bridge> ... [param]]        Show bridge state for the CIST
	showmstilist          <bridge>                             Show list of registered MSTIs
	showmstconfid         <bridge>                             Show MST ConfigId
	showvid2fid           <bridge>                             Show VID-to-FID allocation table
	showfid2mstid         <bridge>                             Show FID-to-MSTID allocation table
	showport              <bridge> [json] [<port> ... [param]] Show port state for the CIST
	showportdetail        <bridge> [json] [<port> ... [param]] Show port detailed state for the CIST
	showtree              <bridge> <mstid>                     Show bridge state for the given MSTI
	showtreeport          <bridge> <port> <mstid>              Show port detailed state for the given MSTI
	setmstconfid          <bridge> <revision> <name>           Set MST ConfigId elements: Revision Level (0-65535) and Name
	setvid2fid            <bridge> <FID>:<VIDs List>           Set VIDs-to-FIDs allocation
	setfid2mstid          <bridge> <mstid>:<FIDs List>         Set FIDs-to-MSTIDs allocation
	setmaxage             <bridge> <max_age>                   Set bridge max age (6-40)
	setfdelay             <bridge> <fwd_delay>                 Set bridge forward delay (4-30)
	setmaxhops            <bridge> <max_hops>                  Set bridge max hops (6-40)
	setforcevers          <bridge> {mstp|rstp|stp}             Force Spanning Tree protocol version
	settxholdcount        <bridge> <tx_hold_count>             Set bridge transmit hold count (1-10)
	createtree            <bridge> <mstid>                     Create new MSTI
	deletetree            <bridge> <mstid>                     Delete existing MSTI
	settreeprio           <bridge> <mstid> <priority>          Set bridge priority (0-65535) for the given MSTI
	setportpathcost       <bridge> <port> <cost>               Set port external path cost for the CIST (0 = auto)
	setportadminedge      <bridge> <port> {yes|no}             Set initial edge state
	setportautoedge       <bridge> <port> {yes|no}             Enable auto transition to/from edge state
	setportp2p            <bridge> <port> {yes|no|auto}        Set p2p detection mode
	setportrestrrole      <bridge> <port> {yes|no}             Restrict port ability to take Root role
	setportrestrtcn       <bridge> <port> {yes|no}             Restrict port ability to propagate received TCNs
	portmcheck            <bridge> <port>                      Try to get back from STP to rapid (RSTP/MSTP) mode
	setbpduguard          <bridge> <port> {yes|no}             Set bpdu guard state
	settreeportprio       <bridge> <port> <mstid> <priority>   Set port priority (0-240) for the given MSTI
	settreeportcost       <bridge> <port> <mstid> <cost>       Set port internal path cost for the given MSTI (0 = auto)
	showall               [json]                               Show detailed mstpctl info
	sethello              <bridge> <hello_time>                Set bridge hello time (1-10)
	setageing             <bridge> <ageing_time>               Set bridge ageing time (10-1000000)
	setportnetwork        <bridge> <port> {yes|no}             Set port network state
	setportbpdufilter     <bridge> <port> {yes|no}             Set BPDU filter state
	debuglevel            <level>                              Level of verbosity (1-4)

```
## cat /proc/net/vlan/config
```

cat: /proc/net/vlan/config: No such file or directory

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

cat: /proc/net/vlan/config: No such file or directory

```
## cat /proc/net/bonding/bond2
```

cat: /proc/net/bonding/bond2: No such file or directory

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

cat: /proc/net/bonding/bond2: No such file or directory

```
