# Filters and Access Lists
## cat sample_count.rules
```

cat: sample_count.rules: No such file or directory

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

cat: sample_count.rules: No such file or directory

```
## sudo cl-acltool -i -p sample_count.rules
```

warning: Detected platform is Cumulus VX
warning: Running in no-hw-sync mode. No rules will be programmed in hw
error: Cannot find policy files: ['sample_count.rules']
```
```

usage: cl-acltool [-h]
                  (-i | -F {all,ip,ip6,eb} | -Z {all,ip,ip6,eb} | -L {all,ip,ip6,eb} | -V)
                  [-p POLICY_FILE] [-P POLICY_DIR] [-n] [-N] [-v] [-x]
                  [--last-good]

acl policy and rule administration

optional arguments:
  -h, --help            show this help message and exit
  -i, --install         Install acl rules
  -F {all,ip,ip6,eb}, --flush {all,ip,ip6,eb}
                        flush rules
  -Z {all,ip,ip6,eb}, --zero-counters {all,ip,ip6,eb}
                        Zero counters
  -L {all,ip,ip6,eb}, --list {all,ip,ip6,eb}
                        List rules
  -V, --version         show version
  -p POLICY_FILE, --policy POLICY_FILE
                        acl policy file name
  -P POLICY_DIR, --policy-dir POLICY_DIR
                        policy dir.
  -n, --dry-run         dry run
  -N, --numeric         do not resolve hostnames
  -v, --verbose         verbose
  -x, --exact           expand numbers (display exact values)
  --last-good           install last good acl policies

```
## sudo iptables -L -v
```

Chain INPUT (policy ACCEPT 0 packets, 0 bytes)
 pkts bytes target     prot opt in     out     source               destination         
    0     0 DROP       all  --  swp+   any     240.0.0.0/5          anywhere            
    0     0 DROP       all  --  swp+   any     loopback/8           anywhere            
    0     0 DROP       all  --  swp+   any     base-address.mcast.net/4  anywhere            
    0     0 DROP       all  --  swp+   any     255.255.255.255      anywhere            
    0     0 SETCLASS   udp  --  swp+   any     anywhere             anywhere             udp dpt:3785 SETCLASS  class:7
    0     0 POLICE     udp  --  any    any     anywhere             anywhere             udp dpt:3785 POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   udp  --  swp+   any     anywhere             anywhere             udp dpt:3784 SETCLASS  class:7
    0     0 POLICE     udp  --  any    any     anywhere             anywhere             udp dpt:3784 POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   udp  --  swp+   any     anywhere             anywhere             udp dpt:4784 SETCLASS  class:7
    0     0 POLICE     udp  --  any    any     anywhere             anywhere             udp dpt:4784 POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   ospf --  swp+   any     anywhere             anywhere             SETCLASS  class:7
    0     0 POLICE     ospf --  any    any     anywhere             anywhere             POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   pim  --  swp+   any     anywhere             anywhere             SETCLASS  class:6
    0     0 POLICE     pim  --  any    any     anywhere             anywhere             POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   tcp  --  swp+   any     anywhere             anywhere             tcp dpt:639 SETCLASS  class:6
    0     0 POLICE     tcp  --  any    any     anywhere             anywhere             tcp dpt:639 POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   tcp  --  swp+   any     anywhere             anywhere             tcp spt:639 SETCLASS  class:6
    0     0 POLICE     tcp  --  any    any     anywhere             anywhere             tcp spt:639 POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   tcp  --  swp+   any     anywhere             anywhere             tcp dpt:bgp SETCLASS  class:7
    0     0 POLICE     tcp  --  any    any     anywhere             anywhere             tcp dpt:bgp POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   tcp  --  swp+   any     anywhere             anywhere             tcp spt:bgp SETCLASS  class:7
    0     0 POLICE     tcp  --  any    any     anywhere             anywhere             tcp spt:bgp POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   tcp  --  swp+   any     anywhere             anywhere             tcp dpt:5342 SETCLASS  class:7
    0     0 POLICE     tcp  --  any    any     anywhere             anywhere             tcp dpt:5342 POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   tcp  --  swp+   any     anywhere             anywhere             tcp spt:5342 SETCLASS  class:7
    0     0 POLICE     tcp  --  any    any     anywhere             anywhere             tcp spt:5342 POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   icmp --  swp+   any     anywhere             anywhere             SETCLASS  class:2
    0     0 POLICE     icmp --  any    any     anywhere             anywhere             POLICE  mode:pkt rate:100 burst:40
    0     0 SETCLASS   udp  --  swp+   any     anywhere             anywhere             udp dpts:bootps:bootpc SETCLASS  class:2
    0     0 POLICE     udp  --  any    any     anywhere             anywhere             udp dpt:bootps POLICE  mode:pkt rate:100 burst:100
    0     0 POLICE     udp  --  any    any     anywhere             anywhere             udp dpt:bootpc POLICE  mode:pkt rate:100 burst:100
    0     0 SETCLASS   tcp  --  swp+   any     anywhere             anywhere             tcp dpts:bootps:bootpc SETCLASS  class:2
    0     0 POLICE     tcp  --  any    any     anywhere             anywhere             tcp dpt:bootps POLICE  mode:pkt rate:100 burst:100
    0     0 POLICE     tcp  --  any    any     anywhere             anywhere             tcp dpt:bootpc POLICE  mode:pkt rate:100 burst:100
    0     0 SETCLASS   udp  --  swp+   any     anywhere             anywhere             udp dpt:10001 SETCLASS  class:3
    0     0 POLICE     udp  --  any    any     anywhere             anywhere             udp dpt:10001 POLICE  mode:pkt rate:2000 burst:2000
    0     0 SETCLASS   igmp --  swp+   any     anywhere             anywhere             SETCLASS  class:6
    0     0 POLICE     igmp --  any    any     anywhere             anywhere             POLICE  mode:pkt rate:300 burst:100
    0     0 POLICE     all  --  swp+   any     anywhere             anywhere             ADDRTYPE match dst-type LOCAL POLICE  mode:pkt rate:1000 burst:1000 class:0
    0     0 POLICE     all  --  swp+   any     anywhere             anywhere             ADDRTYPE match dst-type IPROUTER POLICE  mode:pkt rate:400 burst:100 class:0
    0     0 SETCLASS   all  --  swp+   any     anywhere             anywhere             SETCLASS  class:0

Chain FORWARD (policy ACCEPT 30498 packets, 12M bytes)
 pkts bytes target     prot opt in     out     source               destination         
    0     0 DROP       all  --  swp+   any     240.0.0.0/5          anywhere            
    0     0 DROP       all  --  swp+   any     loopback/8           anywhere            
    0     0 DROP       all  --  swp+   any     base-address.mcast.net/4  anywhere            
    0     0 DROP       all  --  swp+   any     255.255.255.255      anywhere            

Chain OUTPUT (policy ACCEPT 59678 packets, 18M bytes)
 pkts bytes target     prot opt in     out     source               destination         

```
```

iptables v1.4.21

Usage: iptables -[ACD] chain rule-specification [options]
       iptables -I chain [rulenum] rule-specification [options]
       iptables -R chain rulenum rule-specification [options]
       iptables -D chain rulenum [options]
       iptables -[LS] [chain [rulenum]] [options]
       iptables -[FZ] [chain] [options]
       iptables -[NX] chain
       iptables -E old-chain-name new-chain-name
       iptables -P chain target [options]
       iptables -h (print this help information)

Commands:
Either long or short options are allowed.
  --append  -A chain		Append to chain
  --check   -C chain		Check for the existence of a rule
  --delete  -D chain		Delete matching rule from chain
  --delete  -D chain rulenum
				Delete rule rulenum (1 = first) from chain
  --insert  -I chain [rulenum]
				Insert in chain as rulenum (default 1=first)
  --replace -R chain rulenum
				Replace rule rulenum (1 = first) in chain
  --list    -L [chain [rulenum]]
				List the rules in a chain or all chains
  --list-rules -S [chain [rulenum]]
				Print the rules in a chain or all chains
  --flush   -F [chain]		Delete all rules in  chain or all chains
  --zero    -Z [chain [rulenum]]
				Zero counters in chain or all chains
  --new     -N chain		Create a new user-defined chain
  --delete-chain
            -X [chain]		Delete a user-defined chain
  --policy  -P chain target
				Change policy on chain to target
  --rename-chain
            -E old-chain new-chain
				Change chain name, (moving any references)
Options:
    --ipv4	-4		Nothing (line is ignored by ip6tables-restore)
    --ipv6	-6		Error (line is ignored by iptables-restore)
[!] --protocol	-p proto	protocol: by number or name, eg. `tcp'
[!] --source	-s address[/mask][...]
				source specification
[!] --destination -d address[/mask][...]
				destination specification
[!] --in-interface -i input name[+]
				network interface name ([+] for wildcard)
 --jump	-j target
				target for rule (may load target extension)
  --goto      -g chain
                              jump to chain with no return
  --match	-m match
				extended match (may load extension)
  --numeric	-n		numeric output of addresses and ports
[!] --out-interface -o output name[+]
				network interface name ([+] for wildcard)
  --table	-t table	table to manipulate (default: `filter')
  --verbose	-v		verbose mode
  --wait	-w		wait for the xtables lock
  --line-numbers		print line numbers when listing
  --exact	-x		expand numbers (display exact values)
[!] --fragment	-f		match second or further fragments only
  --modprobe=<command>		try to insert modules using this command
  --set-counters PKTS BYTES	set the counter during insert/append
[!] --version	-V		print package version.

```
## sudo cl-acltool
```

usage: cl-acltool [-h]
                  (-i | -F {all,ip,ip6,eb} | -Z {all,ip,ip6,eb} | -L {all,ip,ip6,eb} | -V)
                  [-p POLICY_FILE] [-P POLICY_DIR] [-n] [-N] [-v] [-x]
                  [--last-good]
cl-acltool: error: one of the arguments -i/--install -F/--flush -Z/--zero-counters -L/--list -V/--version is required

```
```

usage: cl-acltool [-h]
                  (-i | -F {all,ip,ip6,eb} | -Z {all,ip,ip6,eb} | -L {all,ip,ip6,eb} | -V)
                  [-p POLICY_FILE] [-P POLICY_DIR] [-n] [-N] [-v] [-x]
                  [--last-good]

acl policy and rule administration

optional arguments:
  -h, --help            show this help message and exit
  -i, --install         Install acl rules
  -F {all,ip,ip6,eb}, --flush {all,ip,ip6,eb}
                        flush rules
  -Z {all,ip,ip6,eb}, --zero-counters {all,ip,ip6,eb}
                        Zero counters
  -L {all,ip,ip6,eb}, --list {all,ip,ip6,eb}
                        List rules
  -V, --version         show version
  -p POLICY_FILE, --policy POLICY_FILE
                        acl policy file name
  -P POLICY_DIR, --policy-dir POLICY_DIR
                        policy dir.
  -n, --dry-run         dry run
  -N, --numeric         do not resolve hostnames
  -v, --verbose         verbose
  -x, --exact           expand numbers (display exact values)
  --last-good           install last good acl policies

```
## sudo cl-acltool -i  -P /etc/cumulus/acl/policy.d/span.rules
```

warning: Detected platform is Cumulus VX
warning: Running in no-hw-sync mode. No rules will be programmed in hw
error: Cannot find policy dir /etc/cumulus/acl/policy.d/span.rules
```
```

usage: cl-acltool [-h]
                  (-i | -F {all,ip,ip6,eb} | -Z {all,ip,ip6,eb} | -L {all,ip,ip6,eb} | -V)
                  [-p POLICY_FILE] [-P POLICY_DIR] [-n] [-N] [-v] [-x]
                  [--last-good]

acl policy and rule administration

optional arguments:
  -h, --help            show this help message and exit
  -i, --install         Install acl rules
  -F {all,ip,ip6,eb}, --flush {all,ip,ip6,eb}
                        flush rules
  -Z {all,ip,ip6,eb}, --zero-counters {all,ip,ip6,eb}
                        Zero counters
  -L {all,ip,ip6,eb}, --list {all,ip,ip6,eb}
                        List rules
  -V, --version         show version
  -p POLICY_FILE, --policy POLICY_FILE
                        acl policy file name
  -P POLICY_DIR, --policy-dir POLICY_DIR
                        policy dir.
  -n, --dry-run         dry run
  -N, --numeric         do not resolve hostnames
  -v, --verbose         verbose
  -x, --exact           expand numbers (display exact values)
  --last-good           install last good acl policies

```
## sudo cl-acltool -L all | grep SPAN
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
Traceback (most recent call last):
  File "/usr/cumulus/bin/cl-acltool", line 1349, in <module>
    log_warn('Detected platform is Cumulus VX')
  File "/usr/cumulus/bin/cl-acltool", line 107, in log_warn
    log_handler("warn", ''.join(args))
  File "/usr/cumulus/bin/cl-acltool", line 65, in log_handler_stdout
    sys.stdout.flush()
IOError: [Errno 32] Broken pipe


```
## sudo cl-acltool -i
```

warning: Detected platform is Cumulus VX
warning: Running in no-hw-sync mode. No rules will be programmed in hw
Reading rule file /etc/cumulus/acl/policy.d/00control_plane.rules ...
Processing rules in file /etc/cumulus/acl/policy.d/00control_plane.rules ...
Reading rule file /etc/cumulus/acl/policy.d/99control_plane_catch_all.rules ...
Processing rules in file /etc/cumulus/acl/policy.d/99control_plane_catch_all.rules ...
Installing acl policy
done.

```
```

usage: cl-acltool [-h]
                  (-i | -F {all,ip,ip6,eb} | -Z {all,ip,ip6,eb} | -L {all,ip,ip6,eb} | -V)
                  [-p POLICY_FILE] [-P POLICY_DIR] [-n] [-N] [-v] [-x]
                  [--last-good]

acl policy and rule administration

optional arguments:
  -h, --help            show this help message and exit
  -i, --install         Install acl rules
  -F {all,ip,ip6,eb}, --flush {all,ip,ip6,eb}
                        flush rules
  -Z {all,ip,ip6,eb}, --zero-counters {all,ip,ip6,eb}
                        Zero counters
  -L {all,ip,ip6,eb}, --list {all,ip,ip6,eb}
                        List rules
  -V, --version         show version
  -p POLICY_FILE, --policy POLICY_FILE
                        acl policy file name
  -P POLICY_DIR, --policy-dir POLICY_DIR
                        policy dir.
  -n, --dry-run         dry run
  -N, --numeric         do not resolve hostnames
  -v, --verbose         verbose
  -x, --exact           expand numbers (display exact values)
  --last-good           install last good acl policies

```
## sudo iptables -L -v | grep SPAN
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
## sudo rm  /etc/cumulus/acl/policy.d/span.rules
```

rm: cannot remove ‘/etc/cumulus/acl/policy.d/span.rules’: No such file or directory

```
```

Usage: rm [OPTION]... FILE...
Remove (unlink) the FILE(s).

  -f, --force           ignore nonexistent files and arguments, never prompt
  -i                    prompt before every removal
  -I                    prompt once before removing more than three files, or
                          when removing recursively; less intrusive than -i,
                          while still giving protection against most mistakes
      --interactive[=WHEN]  prompt according to WHEN: never, once (-I), or
                          always (-i); without WHEN, prompt always
      --one-file-system  when removing a hierarchy recursively, skip any
                          directory that is on a file system different from
                          that of the corresponding command line argument
      --no-preserve-root  do not treat '/' specially
      --preserve-root   do not remove '/' (default)
  -r, -R, --recursive   remove directories and their contents recursively
  -d, --dir             remove empty directories
  -v, --verbose         explain what is being done
      --help     display this help and exit
      --version  output version information and exit

By default, rm does not remove directories.  Use the --recursive (-r or -R)
option to remove each listed directory, too, along with all of its contents.

To remove a file whose name starts with a '-', for example '-foo',
use one of these commands:
  rm -- -foo

  rm ./-foo

Note that if you use rm to remove a file, it might be possible to recover
some of its contents, given sufficient expertise and/or time.  For greater
assurance that the contents are truly unrecoverable, consider using shred.

GNU coreutils online help: <http://www.gnu.org/software/coreutils/>
Full documentation at: <http://www.gnu.org/software/coreutils/rm>
or available locally via: info '(coreutils) rm invocation'

rm: cannot remove ‘/etc/cumulus/acl/policy.d/span.rules’: No such file or directory

```
## sudo tcpdump -i bond0 host 169.254.0.2 -c 10
```

tcpdump: bond0: No such device exists
(SIOCGIFHWADDR: No such device)

```
```

tcpdump version 4.9.2
libpcap version 1.8.1
OpenSSL 1.0.1t  3 May 2016
Usage: tcpdump [-aAbdDefhHIJKlLnNOpqStuUvxX#] [ -B size ] [ -c count ]
		[ -C file_size ] [ -E algo:secret ] [ -F file ] [ -G seconds ]
		[ -i interface ] [ -j tstamptype ] [ -M secret ] [ --number ]
		[ -Q in|out|inout ]
		[ -r file ] [ -s snaplen ] [ --time-stamp-precision precision ]
		[ --immediate-mode ] [ -T type ] [ --version ] [ -V file ]
		[ -w file ] [ -W filecount ] [ -y datalinktype ] [ -z postrotate-command ]
		[ -Z user ] [ expression ]

```
