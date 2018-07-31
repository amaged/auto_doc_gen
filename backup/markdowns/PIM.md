# PIM
## net show mroute
```

pimd is not running

```
```

The following commands contain keyword(s) 'show', 'mroute'

    net show mroute [count|json]
    net show mroute vrf <text> [count|json]


```
## net show pim local-membership
```

pimd is not running

```
```

The following commands contain keyword(s) 'show', 'pim', 'local-membership'

    net show pim (join|local-membership|rpf|rp-info|upstream|upstream-join-desired|upstream-rpf) [json]
    net show pim vrf <text> (join|local-membership|rpf|rp-info|upstream|upstream-join-desired|upstream-rpf) [json]


```
## net show pim state
```

pimd is not running

```
```

The following commands contain keyword(s) 'show', 'pim', 'state'

    net show pim state <ipv4-source> <ipv4-mcast-group> [json]
    net show pim state <ipv4-source> [json]
    net show pim state [json]
    net show pim vrf <text> state <ipv4-source> <ipv4-mcast-group> [json]
    net show pim vrf <text> state <ipv4-source> [json]
    net show pim vrf <text> state [json]


```
## net show pim upstream
```

pimd is not running

```
```

The following commands contain keyword(s) 'show', 'pim', 'upstream'

    net show pim (join|local-membership|rpf|rp-info|upstream|upstream-join-desired|upstream-rpf) [json]
    net show pim vrf <text> (join|local-membership|rpf|rp-info|upstream|upstream-join-desired|upstream-rpf) [json]


```
## net show pim upstream-join-desired
```

pimd is not running

```
```

The following commands contain keyword(s) 'show', 'pim', 'upstream-join-desired'

    net show pim (join|local-membership|rpf|rp-info|upstream|upstream-join-desired|upstream-rpf) [json]
    net show pim vrf <text> (join|local-membership|rpf|rp-info|upstream|upstream-join-desired|upstream-rpf) [json]


```
## net show igmp groups
```

pimd is not running

```
```

The following commands contain keyword(s) 'show', 'igmp', 'groups'

    net show igmp groups [json]
    net show igmp vrf <text> groups [json]


```
## net show igmp sources
```

pimd is not running

```
```

The following commands contain keyword(s) 'show', 'igmp', 'sources'

    net show igmp (join|sources)
    net show igmp vrf <text> (join|sources)


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
## cat  /etc/frr/frr.conf
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
## net show mroute vrf blue
```

pimd is not running

```
```

ERROR: There are no commands with keyword(s) 'show', 'mroute', 'vrf', 'blue'

```
## cl-resource-query  | grep Mcast
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
nohup: failed to run command ‘cl-resource-query’: No such file or directory


```
## net show msdp sa
```

pimd is not running

```
```

The following commands contain keyword(s) 'show', 'msdp', 'sa'

    net show msdp sa <ipv4> <ipv4-mcast-group> [json]
    net show msdp sa <ipv4> [json]
    net show msdp sa [detail] [json]
    net show msdp vrf <text> sa <ipv4> <ipv4-mcast-group> [json]
    net show msdp vrf <text> sa <ipv4> [json]
    net show msdp vrf <text> sa [detail] [json]


```
