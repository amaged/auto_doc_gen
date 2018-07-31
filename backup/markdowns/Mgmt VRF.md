# Mgmt VRF
## sudo nano /etc/vrf/systemd.conf
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
## ps aux | grep flow
```

cumulus   7025  0.0  0.0  12728  2132 ?        S    19:49   0:00 grep flow

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

cumulus   7025  0.0  0.0  12728  2132 ?        S    19:49   0:00 grep flow

```
## ping -I mgmt
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
## sudo traceroute -i mgmt
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
## cat  /etc/systemd/system/myservice.service
```

cat: /etc/systemd/system/myservice.service: No such file or directory

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

cat: /etc/systemd/system/myservice.service: No such file or directory

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
## net show route vrf mgmt
```


show ip route vrf mgmt 
=======================
% VRF mgmt not found


show ipv6 route vrf mgmt 
=========================
% VRF mgmt not found

```
```

ERROR: There are no commands with keyword(s) 'show', 'route', 'vrf', 'mgmt'

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
## ifquery l --allow=mgmt
```

error: '--allow' option is mutually exclusive with interface list and '-a'

```
```

nohup: failed to run command ‘ifquery’: No such file or directory

```
## cat  /etc/resolv.conf
```

nameserver 8.8.8.8

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

nameserver 8.8.8.8

```
## cl-ns-mgmt
```

nohup: failed to run command ‘cl-ns-mgmt’: No such file or directory

```
```

nohup: failed to run command ‘cl-ns-mgmt’: No such file or directory

```
