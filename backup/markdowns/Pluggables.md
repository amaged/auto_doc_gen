# Pluggables
## net show int pluggables
```


Interface    Identifier    Vendor Name    Vendor PN    Vendor SN    Vendor Rev
-----------  ------------  -------------  -----------  -----------  ------------


```
```

The following commands contain keyword(s) 'show', 'int', 'pluggables'

    net show interface pluggables [json]


```
## sudo ethtool -S %DP
```

Cannot get stats strings information: No such device

```
```

ethtool: bad command line argument(s)
For more information run ethtool -h

```
## sudo cl-netstat
```


Kernel Interface table
Iface      MTU    Met    RX_OK    RX_ERR    RX_DRP    RX_OVR    TX_OK    TX_ERR    TX_DRP    TX_OVR  Flg
-------  -----  -----  -------  --------  --------  --------  -------  --------  --------  --------  -----
docker0   1500      0        0         0         0         0        0         0         0         0  BMU
eth0      1500      0    22515         0         0         0    22589         0         0         0  BMRU
eth1      1500      0    63100         0         0         0    51499         0         0         0  BMRU
eth2      1500      0     4017         0         2         0     4222         0         0         0  BMRU
eth3      1500      0     4156         0         1         0     3949         0         0         0  BMRU
lo       65536      0    19791         0         0         0    19791         0         0         0  LRU


```
```

usage: cl-netstat [-h] [-v] [-c] [-d] [-D] [-j] [-r] [-t TAG]
                  [--clear-interface CLEAR_INTERFACE]

Wrapper for netstat

optional arguments:
  -h, --help            show this help message and exit
  -v, --version         show program's version number and exit
  -c, --clear           Copy & clear stats per user (tag)
  -d, --delete          Delete saved stats, either the uid or the specified tag
  -D, --delete-all      Delete all saved stats
  -j, --json            Display in JSON format
  -r, --raw             Raw stats (unmodified output of netstat)
  -t TAG, --tag TAG     Save stats with name TAG
  --clear-interface CLEAR_INTERFACE
                        clear stats for a single interface

Note: Clearing stats does not affect hardware or software values.
      cl-netstat saves the current stats when -c is given, so they can
      be compared with later values.  The -c and -d options are per user (UID)
      by default.  Use the -t TAG option to change this behavior.  You must
      use the same -t TAG value with subsequent commands to get valid results.

Examples:
  cl-netstat -c -t test
  cl-netstat -t test
  cl-netstat -d -t test
  cl-netstat
  cl-netstat -r

```
