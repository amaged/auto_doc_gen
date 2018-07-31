# VXLAN
## netq show vxlan
```


No matching vxlan records found

```
```

The following commands contain keyword(s) 'show', 'vxlan'

    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) [count] [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) around <text-time> [count] [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) changes [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) state <remote-interface-state> [count] [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) state <remote-interface-state> around <text-time> [count] [json]
    netq [<hostname>] show vxlan [json]
    netq [<hostname>] show vxlan around <text-time> [json]
    netq [<hostname>] show vxlan changes [json]
    netq [<hostname>] show vxlan changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show vxlan vni <text-vni> [json]
    netq [<hostname>] show vxlan vni <text-vni> around <text-time> [json]
    netq [<hostname>] show vxlan vni <text-vni> changes [json]
    netq [<hostname>] show vxlan vni <text-vni> changes between <text-time> and <text-endtime> [json]


Unable to find command netq show vxlan --help


No matching vxlan records found

```
## netq check vxlan
```

No VXLAN info found

```
```

The following commands contain keyword(s) 'check', 'vxlan'

    netq check vxlan [json]
    netq check vxlan around <text-time> [json]


Unable to find command netq check vxlan --help

No VXLAN info found

```
## sudo bridge fdb show | grep 00:00:00:00:00:00
```


```
```

Usage: grep [OPTION]... PATTERN [FILE]...
Search for PATTERN in each FILE or standard input.
PATTERN is, by default, a basic regular expression (BRE).
Example: grep -i 'hello world' menu.h main.c

Regexp selection and interpretation:
  -E, --extended-regexp     PATTERN is an extended regular expression (ERE)
  -F, --fixed-strings       PATTERN is a set of newline-separated fixed strings
  -G, --basic-regexp        PATTERN is a basic regular expression (BRE)
  -P, --perl-regexp         PATTERN is a Perl regular expression
  -e, --regexp=PATTERN      use PATTERN for matching
  -f, --file=FILE           obtain PATTERN from FILE
  -i, --ignore-case         ignore case distinctions
  -w, --word-regexp         force PATTERN to match only whole words
  -x, --line-regexp         force PATTERN to match only whole lines
  -z, --null-data           a data line ends in 0 byte, not newline

Miscellaneous:
  -s, --no-messages         suppress error messages
  -v, --invert-match        select non-matching lines
  -V, --version             display version information and exit
      --help                display this help text and exit

Output control:
  -m, --max-count=NUM       stop after NUM matches
  -b, --byte-offset         print the byte offset with output lines
  -n, --line-number         print line number with output lines
      --line-buffered       flush output on every line
  -H, --with-filename       print the file name for each match
  -h, --no-filename         suppress the file name prefix on output
      --label=LABEL         use LABEL as the standard input file name prefix
  -o, --only-matching       show only the part of a line matching PATTERN
  -q, --quiet, --silent     suppress all normal output
      --binary-files=TYPE   assume that binary files are TYPE;
                            TYPE is 'binary', 'text', or 'without-match'
  -a, --text                equivalent to --binary-files=text
  -I                        equivalent to --binary-files=without-match
  -d, --directories=ACTION  how to handle directories;
                            ACTION is 'read', 'recurse', or 'skip'
  -D, --devices=ACTION      how to handle devices, FIFOs and sockets;
                            ACTION is 'read' or 'skip'
  -r, --recursive           like --directories=recurse
  -R, --dereference-recursive  likewise, but follow all symlinks
      --include=FILE_PATTERN  search only files that match FILE_PATTERN
      --exclude=FILE_PATTERN  skip files and directories matching FILE_PATTERN
      --exclude-from=FILE   skip files matching any file pattern from FILE
      --exclude-dir=PATTERN  directories that match PATTERN will be skipped.
  -L, --files-without-match  print only names of FILEs containing no match
  -l, --files-with-matches  print only names of FILEs containing matches
  -c, --count               print only a count of matching lines per FILE
  -T, --initial-tab         make tabs line up (if needed)
  -Z, --null                print 0 byte after FILE name

Context control:
  -B, --before-context=NUM  print NUM lines of leading context
  -A, --after-context=NUM   print NUM lines of trailing context
  -C, --context=NUM         print NUM lines of output context
  -NUM                      same as --context=NUM
      --color[=WHEN],
      --colour[=WHEN]       use markers to highlight the matching strings;
                            WHEN is 'always', 'never', or 'auto'
  -U, --binary              do not strip CR characters at EOL (MSDOS/Windows)
  -u, --unix-byte-offsets   report offsets as if CRs were not there
                            (MSDOS/Windows)

'egrep' means 'grep -E'.  'fgrep' means 'grep -F'.
Direct invocation as either 'egrep' or 'fgrep' is deprecated.
When FILE is -, read standard input.  With no FILE, read . if a command-line
-r is given, - otherwise.  If fewer than two FILEs are given, assume -h.
Exit status is 0 if any line is selected, 1 otherwise;
if any error occurs and -q is not given, the exit status is 2.

Report bugs to: bug-grep@gnu.org
GNU Grep home page: <http://www.gnu.org/software/grep/>
General help using GNU software: <http://www.gnu.org/gethelp/>


```
## brctl show
```

bridge name	bridge id		STP enabled	interfaces
docker0		8000.02420d8c0822	no		

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
## ip –d link show vni-10
```

Object "–d" is unknown, try "ip help".

```
```

Object "–d" is unknown, try "ip help".

```
## sudo systemctl status vxsnd.service
```

● vxsnd.service - Lightweight Network Virt Discovery Svc and Replicator
   Loaded: loaded (/lib/systemd/system/vxsnd.service; disabled)
   Active: inactive (dead)

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
## cat /etc/vxsnd.conf
```

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

```
## vxrdctl vxlans
```

Unable to connect to daemon on socket /var/run/vxrd.sock [2]: No such file or directory

```
```

    Usage:
        vxrdctl -h
        vxrdctl [-u UDS_FILE] [-j] get config [<parameter>]
        vxrdctl [-u UDS_FILE] [-j] vxlans [hrep] [<vni>]
        vxrdctl [-u UDS_FILE] [-j] peers [<vni>]
        vxrdctl [-u UDS_FILE] [-j] show

    Options:
        -h, --help   : Show this screen and exit
        -u UDS_FILE  : File name for Unix domain socket
                       [default: /var/run/vxrd.sock]
        -j           : Print result as json string

    Commands:
        get config: print the vxrd configuration
        get config <parameter>: print single vxrd config option
        vxlans: get the current set of vxlans the RD has reported to the snd
        vxlans hrep: print the HREP addrs for the vxlan devices
        peers:  get the list of vtep peers reported back by the snd
        peers <vni>:  get the list of vtep peers reported back by the snd for
                      a vni
        show: print a snapshot of the runtime configuration
    

```
## vxrdctl peers
```

Unable to connect to daemon on socket /var/run/vxrd.sock [2]: No such file or directory

```
```

    Usage:
        vxrdctl -h
        vxrdctl [-u UDS_FILE] [-j] get config [<parameter>]
        vxrdctl [-u UDS_FILE] [-j] vxlans [hrep] [<vni>]
        vxrdctl [-u UDS_FILE] [-j] peers [<vni>]
        vxrdctl [-u UDS_FILE] [-j] show

    Options:
        -h, --help   : Show this screen and exit
        -u UDS_FILE  : File name for Unix domain socket
                       [default: /var/run/vxrd.sock]
        -j           : Print result as json string

    Commands:
        get config: print the vxrd configuration
        get config <parameter>: print single vxrd config option
        vxlans: get the current set of vxlans the RD has reported to the snd
        vxlans hrep: print the HREP addrs for the vxlan devices
        peers:  get the list of vtep peers reported back by the snd
        peers <vni>:  get the list of vtep peers reported back by the snd for
                      a vni
        show: print a snapshot of the runtime configuration
    

```
## vxsndctl fdb
```

Unable to connect to daemon on socket /var/run/vxsnd.sock [2]: No such file or directory

```
```

    Usage:
        vxsndctl -h
        vxsndctl [-u UDS_FILE] [-j] fdb [debug]
        vxsndctl [-u UDS_FILE] [-j] fdb [<vni>] [debug]
        vxsndctl [-u UDS_FILE] [-j] fdb (add <vni> <ip> | del <vni> <ip> |
                                         file <filename>)
        vxsndctl [-u UDS_FILE] [-j] get config [<parameter>]
        vxsndctl [-u UDS_FILE] [-j] set config <parameter> [<value>]
        vxsndctl [-u UDS_FILE] [-j] set debug (on | off)
        vxsndctl [-u UDS_FILE] [-j] show [detail]

    Options:
        -h, --help   : Show this screen and exit
        -u UDS_FILE  : File name for Unix domain socket
                       [default: /var/run/vxsnd.sock]
        -j           : Print result as json string

    Commands:
        fdb: print the vxsnd forwarding DB
        fdb <vni>: print the vxsnd forwarding DB for a vni
        get config: print the vxsnd configuration
        get config <parameter>: print single vxsnd config option
        set config <parameter> [<value>]: set a single vxsnd config option
        set debug on: enable debug mode and set loglevel to debug
        set debug off: disable debug mode and set loglevel to previous level
        show: print a snapshot of the runtime configuration
        show detail: print a detailed snapshot of the runtime configuration
    

```
## cat /cumulus/switchd/run/stats/vxlan/all
```

cat: /cumulus/switchd/run/stats/vxlan/all: No such file or directory

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

cat: /cumulus/switchd/run/stats/vxlan/all: No such file or directory

```
## ip addr show eth3.10 | grep ether
```

Device "eth3.10" does not exist.

```
```

Device "eth3.10" does not exist.
Usage: grep [OPTION]... PATTERN [FILE]...
Search for PATTERN in each FILE or standard input.
PATTERN is, by default, a basic regular expression (BRE).
Example: grep -i 'hello world' menu.h main.c

Regexp selection and interpretation:
  -E, --extended-regexp     PATTERN is an extended regular expression (ERE)
  -F, --fixed-strings       PATTERN is a set of newline-separated fixed strings
  -G, --basic-regexp        PATTERN is a basic regular expression (BRE)
  -P, --perl-regexp         PATTERN is a Perl regular expression
  -e, --regexp=PATTERN      use PATTERN for matching
  -f, --file=FILE           obtain PATTERN from FILE
  -i, --ignore-case         ignore case distinctions
  -w, --word-regexp         force PATTERN to match only whole words
  -x, --line-regexp         force PATTERN to match only whole lines
  -z, --null-data           a data line ends in 0 byte, not newline

Miscellaneous:
  -s, --no-messages         suppress error messages
  -v, --invert-match        select non-matching lines
  -V, --version             display version information and exit
      --help                display this help text and exit

Output control:
  -m, --max-count=NUM       stop after NUM matches
  -b, --byte-offset         print the byte offset with output lines
  -n, --line-number         print line number with output lines
      --line-buffered       flush output on every line
  -H, --with-filename       print the file name for each match
  -h, --no-filename         suppress the file name prefix on output
      --label=LABEL         use LABEL as the standard input file name prefix
  -o, --only-matching       show only the part of a line matching PATTERN
  -q, --quiet, --silent     suppress all normal output
      --binary-files=TYPE   assume that binary files are TYPE;
                            TYPE is 'binary', 'text', or 'without-match'
  -a, --text                equivalent to --binary-files=text
  -I                        equivalent to --binary-files=without-match
  -d, --directories=ACTION  how to handle directories;
                            ACTION is 'read', 'recurse', or 'skip'
  -D, --devices=ACTION      how to handle devices, FIFOs and sockets;
                            ACTION is 'read' or 'skip'
  -r, --recursive           like --directories=recurse
  -R, --dereference-recursive  likewise, but follow all symlinks
      --include=FILE_PATTERN  search only files that match FILE_PATTERN
      --exclude=FILE_PATTERN  skip files and directories matching FILE_PATTERN
      --exclude-from=FILE   skip files matching any file pattern from FILE
      --exclude-dir=PATTERN  directories that match PATTERN will be skipped.
  -L, --files-without-match  print only names of FILEs containing no match
  -l, --files-with-matches  print only names of FILEs containing matches
  -c, --count               print only a count of matching lines per FILE
  -T, --initial-tab         make tabs line up (if needed)
  -Z, --null                print 0 byte after FILE name

Context control:
  -B, --before-context=NUM  print NUM lines of leading context
  -A, --after-context=NUM   print NUM lines of trailing context
  -C, --context=NUM         print NUM lines of output context
  -NUM                      same as --context=NUM
      --color[=WHEN],
      --colour[=WHEN]       use markers to highlight the matching strings;
                            WHEN is 'always', 'never', or 'auto'
  -U, --binary              do not strip CR characters at EOL (MSDOS/Windows)
  -u, --unix-byte-offsets   report offsets as if CRs were not there
                            (MSDOS/Windows)

'egrep' means 'grep -E'.  'fgrep' means 'grep -F'.
Direct invocation as either 'egrep' or 'fgrep' is deprecated.
When FILE is -, read standard input.  With no FILE, read . if a command-line
-r is given, - otherwise.  If fewer than two FILEs are given, assume -h.
Exit status is 0 if any line is selected, 1 otherwise;
if any error occurs and -q is not given, the exit status is 2.

Report bugs to: bug-grep@gnu.org
GNU Grep home page: <http://www.gnu.org/software/grep/>
General help using GNU software: <http://www.gnu.org/gethelp/>

Device "eth3.10" does not exist.

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
## brctl showmacs br-10
```

read of forward table failed: No such device

```
```

nohup: failed to run command ‘brctl’: No such file or directory

```
## vxrdctl get config
```

Unable to connect to daemon on socket /var/run/vxrd.sock [2]: No such file or directory

```
```

    Usage:
        vxrdctl -h
        vxrdctl [-u UDS_FILE] [-j] get config [<parameter>]
        vxrdctl [-u UDS_FILE] [-j] vxlans [hrep] [<vni>]
        vxrdctl [-u UDS_FILE] [-j] peers [<vni>]
        vxrdctl [-u UDS_FILE] [-j] show

    Options:
        -h, --help   : Show this screen and exit
        -u UDS_FILE  : File name for Unix domain socket
                       [default: /var/run/vxrd.sock]
        -j           : Print result as json string

    Commands:
        get config: print the vxrd configuration
        get config <parameter>: print single vxrd config option
        vxlans: get the current set of vxlans the RD has reported to the snd
        vxlans hrep: print the HREP addrs for the vxlan devices
        peers:  get the list of vtep peers reported back by the snd
        peers <vni>:  get the list of vtep peers reported back by the snd for
                      a vni
        show: print a snapshot of the runtime configuration
    

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
## net show vxlan
```

ERROR: Command not found

net show vxlan
         ^ Invalid value here
Use 'net help KEYWORD(s)' to list all options that use KEYWORD(s)

```
```

ERROR: There are no commands with keyword(s) 'show', 'vxlan'

```
## cat /usr/lib/python2.7/dist-packages/cumulus/__chip_config/bcm/datapath.conf
```

#
# Default datapath configuration for Broadcom chips
# Copyright 2014, 2015, 2016, 2017, Cumulus Networks, Inc.  All rights reserved.
#

# priority group ID assigned to each priority group
priority_group.control.id = 7
priority_group.service.id = 2
priority_group.bulk.id = 0

# service pools assigned to each priority group
priority_group.control.service_pool = 1
priority_group.service.service_pool = 2
priority_group.bulk.service_pool = 0

# --- ingress buffer space allocations ---
#
# total buffer
#  - ingress minimum buffer allocations
#  - ingress service pool buffer allocations
#  - priority group ingress headroom allocations
#  - ingress global headroom allocations
#  = total ingress shared buffer size

# ingress service pool buffer allocation: percent of total buffer
# If a service pool has no priority groups, the buffer is added
# to the shared buffer space.
ingress_service_pool.0.percent = 0.0  # bulk
ingress_service_pool.1.percent = 3.0  # control
ingress_service_pool.2.percent = 2.0  # service

# priority group minimum buffer allocation: percent of total buffer cells
# priority group shared buffer allocation: percent of total shared buffer size
# if a priority group has no packet priority values assigned to it, the buffers will not be allocated

priority_group.control.ingress_buffer.min_percent = 0.0
priority_group.control.ingress_buffer.shared_percent = 44.0

priority_group.service.ingress_buffer.min_percent = 0.0
priority_group.service.ingress_buffer.shared_percent = 4.0

priority_group.bulk.ingress_buffer.min_percent = 40.0
priority_group.bulk.ingress_buffer.shared_percent = 20.0

# ingress buffer limits for ports with pause configured
# this configuration overrides default values
#     default minimum cell limit :  512
#     default shared cell limit  : 1024
# link_pause.port_group_0.minimum_cell_limit = 200
# link_pause.port_group_0.shared_cell_limit  = 600

# --- egress buffer space allocations ---
#
# total egress buffer
#  - minimum buffer allocations
#  = total service pool buffer size
#
# Service pool buffer allocation: percent of total
# buffer size.
egress_service_pool.0.percent = 75.0   # bulk
egress_service_pool.1.percent = 90.0   # control
egress_service_pool.2.percent = 90.0   # service

# Front panel port egress buffer limits enforced for each
# priority group.
priority_group.control.unlimited_egress_buffer = true
priority_group.service.unlimited_egress_buffer = true
priority_group.bulk.unlimited_egress_buffer = false

#
# if a priority group has no cos values assigned to it, the buffers will not be allocated
#

# priority group minimum buffer allocation: percent of total buffer
priority_group.bulk.egress_buffer.uc.min_percent  = 5.0
priority_group.bulk.egress_buffer.mc.min_percent  = 2.0
priority_group.bulk.egress_buffer.cpu.min_percent = 4.0

# Priority group service pool buffer limits: percent of the
# assigned service pool.
priority_group.bulk.egress_buffer.uc.sp_percent = 45.0
priority_group.bulk.egress_buffer.mc.sp_percent = 45.0
priority_group.bulk.egress_buffer.cpu.sp_percent = 10.0

# internal cos values mapped to egress queues
# multicast queue: same as unicast queue
cos_egr_queue.cos_0.uc  = 0
cos_egr_queue.cos_0.cpu = 0

cos_egr_queue.cos_1.uc  = 1
cos_egr_queue.cos_1.cpu = 1

cos_egr_queue.cos_2.uc  = 2
cos_egr_queue.cos_2.cpu = 2

cos_egr_queue.cos_3.uc  = 3
cos_egr_queue.cos_3.cpu = 3

cos_egr_queue.cos_4.uc  = 4
cos_egr_queue.cos_4.cpu = 4

cos_egr_queue.cos_5.uc  = 5
cos_egr_queue.cos_5.cpu = 5

cos_egr_queue.cos_6.uc  = 6
cos_egr_queue.cos_6.cpu = 6

cos_egr_queue.cos_7.uc  = 7
cos_egr_queue.cos_7.cpu = 7

# Enabling/disabling Denial of service (DOS) prevetion checks
# To change the default configuration:
# enable/disable the individual DOS checks.
dos.sip_eq_dip = false
dos.smac_eq_dmac = false
dos.tcp_hdr_partial = false
dos.tcp_syn_frag = false
dos.tcp_ports_eq = false
dos.tcp_flags_syn_fin = false
dos.tcp_flags_fup_seq0 = false
dos.tcp_offset1 = false
dos.tcp_ctrl0_seq0 = false
dos.udp_ports_eq = false
dos.icmp_frag = false
dos.icmpv4_length = false
dos.icmpv6_length = false
dos.ipv6_min_frag = false

# Specify a VxLan Routing Profile - the profile selected determines the
# maximum number of overlay next hops that can be allocated.
# This is supported only on TridentTwoPlus and Maverick
#
# Profile can be one of {'default', 'mode-1', 'mode-2', 'mode-3', 'disable'}
# default: 15% of the overall nexthops are for overlay.
# mode-1:  25% of the overall nexthops are for overlay.
# mode-2:  50% of the overall nexthops are for overlay.
# mode-3:  80% of the overall nexthops are for overlay.
# disable: VxLan Routing is disabled
#
# By default VxLan Routing is enabled with the default profile.
vxlan_routing_overlay.profile = default

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

#
# Default datapath configuration for Broadcom chips
# Copyright 2014, 2015, 2016, 2017, Cumulus Networks, Inc.  All rights reserved.
#

# priority group ID assigned to each priority group
priority_group.control.id = 7
priority_group.service.id = 2
priority_group.bulk.id = 0

# service pools assigned to each priority group
priority_group.control.service_pool = 1
priority_group.service.service_pool = 2
priority_group.bulk.service_pool = 0

# --- ingress buffer space allocations ---
#
# total buffer
#  - ingress minimum buffer allocations
#  - ingress service pool buffer allocations
#  - priority group ingress headroom allocations
#  - ingress global headroom allocations
#  = total ingress shared buffer size

# ingress service pool buffer allocation: percent of total buffer
# If a service pool has no priority groups, the buffer is added
# to the shared buffer space.
ingress_service_pool.0.percent = 0.0  # bulk
ingress_service_pool.1.percent = 3.0  # control
ingress_service_pool.2.percent = 2.0  # service

# priority group minimum buffer allocation: percent of total buffer cells
# priority group shared buffer allocation: percent of total shared buffer size
# if a priority group has no packet priority values assigned to it, the buffers will not be allocated

priority_group.control.ingress_buffer.min_percent = 0.0
priority_group.control.ingress_buffer.shared_percent = 44.0

priority_group.service.ingress_buffer.min_percent = 0.0
priority_group.service.ingress_buffer.shared_percent = 4.0

priority_group.bulk.ingress_buffer.min_percent = 40.0
priority_group.bulk.ingress_buffer.shared_percent = 20.0

# ingress buffer limits for ports with pause configured
# this configuration overrides default values
#     default minimum cell limit :  512
#     default shared cell limit  : 1024
# link_pause.port_group_0.minimum_cell_limit = 200
# link_pause.port_group_0.shared_cell_limit  = 600

# --- egress buffer space allocations ---
#
# total egress buffer
#  - minimum buffer allocations
#  = total service pool buffer size
#
# Service pool buffer allocation: percent of total
# buffer size.
egress_service_pool.0.percent = 75.0   # bulk
egress_service_pool.1.percent = 90.0   # control
egress_service_pool.2.percent = 90.0   # service

# Front panel port egress buffer limits enforced for each
# priority group.
priority_group.control.unlimited_egress_buffer = true
priority_group.service.unlimited_egress_buffer = true
priority_group.bulk.unlimited_egress_buffer = false

#
# if a priority group has no cos values assigned to it, the buffers will not be allocated
#

# priority group minimum buffer allocation: percent of total buffer
priority_group.bulk.egress_buffer.uc.min_percent  = 5.0
priority_group.bulk.egress_buffer.mc.min_percent  = 2.0
priority_group.bulk.egress_buffer.cpu.min_percent = 4.0

# Priority group service pool buffer limits: percent of the
# assigned service pool.
priority_group.bulk.egress_buffer.uc.sp_percent = 45.0
priority_group.bulk.egress_buffer.mc.sp_percent = 45.0
priority_group.bulk.egress_buffer.cpu.sp_percent = 10.0

# internal cos values mapped to egress queues
# multicast queue: same as unicast queue
cos_egr_queue.cos_0.uc  = 0
cos_egr_queue.cos_0.cpu = 0

cos_egr_queue.cos_1.uc  = 1
cos_egr_queue.cos_1.cpu = 1

cos_egr_queue.cos_2.uc  = 2
cos_egr_queue.cos_2.cpu = 2

cos_egr_queue.cos_3.uc  = 3
cos_egr_queue.cos_3.cpu = 3

cos_egr_queue.cos_4.uc  = 4
cos_egr_queue.cos_4.cpu = 4

cos_egr_queue.cos_5.uc  = 5
cos_egr_queue.cos_5.cpu = 5

cos_egr_queue.cos_6.uc  = 6
cos_egr_queue.cos_6.cpu = 6

cos_egr_queue.cos_7.uc  = 7
cos_egr_queue.cos_7.cpu = 7

# Enabling/disabling Denial of service (DOS) prevetion checks
# To change the default configuration:
# enable/disable the individual DOS checks.
dos.sip_eq_dip = false
dos.smac_eq_dmac = false
dos.tcp_hdr_partial = false
dos.tcp_syn_frag = false
dos.tcp_ports_eq = false
dos.tcp_flags_syn_fin = false
dos.tcp_flags_fup_seq0 = false
dos.tcp_offset1 = false
dos.tcp_ctrl0_seq0 = false
dos.udp_ports_eq = false
dos.icmp_frag = false
dos.icmpv4_length = false
dos.icmpv6_length = false
dos.ipv6_min_frag = false

# Specify a VxLan Routing Profile - the profile selected determines the
# maximum number of overlay next hops that can be allocated.
# This is supported only on TridentTwoPlus and Maverick
#
# Profile can be one of {'default', 'mode-1', 'mode-2', 'mode-3', 'disable'}
# default: 15% of the overall nexthops are for overlay.
# mode-1:  25% of the overall nexthops are for overlay.
# mode-2:  50% of the overall nexthops are for overlay.
# mode-3:  80% of the overall nexthops are for overlay.
# disable: VxLan Routing is disabled
#
# By default VxLan Routing is enabled with the default profile.
vxlan_routing_overlay.profile = default

```
## sudo nano /etc/cumulus/ports.conf
```

Error opening terminal: unknown.

```
```

Usage: nano [OPTIONS] [[+LINE,COLUMN] FILE]...

Option		GNU long option		Meaning
 -h, -?		--help			Show this message
 +LINE,COLUMN				Start at line LINE, column COLUMN
 -A		--smarthome		Enable smart home key
 -B		--backup		Save backups of existing files
 -C <dir>	--backupdir=<dir>	Directory for saving unique backup files
 -D		--boldtext		Use bold instead of reverse video text
 -E		--tabstospaces		Convert typed tabs to spaces
 -F		--multibuffer		Enable multiple file buffers
 -H		--historylog		Log & read search/replace string history
 -I		--ignorercfiles		Don't look at nanorc files
 -K		--rebindkeypad		Fix numeric keypad key confusion problem
 -L		--nonewlines		Don't add newlines to the ends of files
 -N		--noconvert		Don't convert files from DOS/Mac format
 -O		--morespace		Use one more line for editing
 -Q <str>	--quotestr=<str>	Quoting string
 -R		--restricted		Restricted mode
 -S		--smooth		Scroll by line instead of half-screen
 -T <#cols>	--tabsize=<#cols>	Set width of a tab to #cols columns
 -U		--quickblank		Do quick statusbar blanking
 -V		--version		Print version information and exit
 -W		--wordbounds		Detect word boundaries more accurately
 -Y <str>	--syntax=<str>		Syntax definition to use for coloring
 -c		--const			Constantly show cursor position
 -d		--rebinddelete		Fix Backspace/Delete confusion problem
 -i		--autoindent		Automatically indent new lines
 -k		--cut			Cut from cursor to end of line
 -l		--nofollow		Don't follow symbolic links, overwrite
 -m		--mouse			Enable the use of the mouse
 -o <dir>	--operatingdir=<dir>	Set operating directory
 -p		--preserve		Preserve XON (^Q) and XOFF (^S) keys
 -q		--quiet			Silently ignore startup issues like rc file errors
 -r <#cols>	--fill=<#cols>		Set wrapping point at column #cols
 -s <prog>	--speller=<prog>	Enable alternate speller
 -t		--tempfile		Auto save on exit, don't prompt
 -u		--undo			Allow generic undo [EXPERIMENTAL]
 -v		--view			View mode (read-only)
 -w		--nowrap		Don't wrap long lines
 -x		--nohelp		Don't show the two help lines
 -z		--suspend		Enable suspension
 -$		--softwrap		Enable soft line wrapping
 -a, -b, -e,				
 -f, -g, -j				(ignored, for Pico compatibility)

```
## sudo nano /etc/cumulus/switchd.conf
```

Error opening terminal: unknown.

```
```

Usage: nano [OPTIONS] [[+LINE,COLUMN] FILE]...

Option		GNU long option		Meaning
 -h, -?		--help			Show this message
 +LINE,COLUMN				Start at line LINE, column COLUMN
 -A		--smarthome		Enable smart home key
 -B		--backup		Save backups of existing files
 -C <dir>	--backupdir=<dir>	Directory for saving unique backup files
 -D		--boldtext		Use bold instead of reverse video text
 -E		--tabstospaces		Convert typed tabs to spaces
 -F		--multibuffer		Enable multiple file buffers
 -H		--historylog		Log & read search/replace string history
 -I		--ignorercfiles		Don't look at nanorc files
 -K		--rebindkeypad		Fix numeric keypad key confusion problem
 -L		--nonewlines		Don't add newlines to the ends of files
 -N		--noconvert		Don't convert files from DOS/Mac format
 -O		--morespace		Use one more line for editing
 -Q <str>	--quotestr=<str>	Quoting string
 -R		--restricted		Restricted mode
 -S		--smooth		Scroll by line instead of half-screen
 -T <#cols>	--tabsize=<#cols>	Set width of a tab to #cols columns
 -U		--quickblank		Do quick statusbar blanking
 -V		--version		Print version information and exit
 -W		--wordbounds		Detect word boundaries more accurately
 -Y <str>	--syntax=<str>		Syntax definition to use for coloring
 -c		--const			Constantly show cursor position
 -d		--rebinddelete		Fix Backspace/Delete confusion problem
 -i		--autoindent		Automatically indent new lines
 -k		--cut			Cut from cursor to end of line
 -l		--nofollow		Don't follow symbolic links, overwrite
 -m		--mouse			Enable the use of the mouse
 -o <dir>	--operatingdir=<dir>	Set operating directory
 -p		--preserve		Preserve XON (^Q) and XOFF (^S) keys
 -q		--quiet			Silently ignore startup issues like rc file errors
 -r <#cols>	--fill=<#cols>		Set wrapping point at column #cols
 -s <prog>	--speller=<prog>	Enable alternate speller
 -t		--tempfile		Auto save on exit, don't prompt
 -u		--undo			Allow generic undo [EXPERIMENTAL]
 -v		--view			View mode (read-only)
 -w		--nowrap		Don't wrap long lines
 -x		--nohelp		Don't show the two help lines
 -z		--suspend		Enable suspension
 -$		--softwrap		Enable soft line wrapping
 -a, -b, -e,				
 -f, -g, -j				(ignored, for Pico compatibility)

```
## cat /etc/default/openvswitch-vtep
```

# This is a POSIX shell fragment                -*- sh -*-

# Start openvswitch at boot ? yes/no
START=no

# FORCE_COREFILES: If 'yes' then core files will be enabled.
# FORCE_COREFILES=yes

# BRCOMPAT: If 'yes' and the openvswitch-brcompat package is installed, then
# Linux bridge compatibility will be enabled.
# BRCOMPAT=no

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

# This is a POSIX shell fragment                -*- sh -*-

# Start openvswitch at boot ? yes/no
START=no

# FORCE_COREFILES: If 'yes' then core files will be enabled.
# FORCE_COREFILES=yes

# BRCOMPAT: If 'yes' and the openvswitch-brcompat package is installed, then
# Linux bridge compatibility will be enabled.
# BRCOMPAT=no

```
