# Layer 1
## sudo ethtool -m %DP
```

Cannot get module EEPROM information: No such device

```
```

ethtool: bad command line argument(s)
For more information run ethtool -h

```
## sudo ethtool %DP
```

Cannot get device settings: No such device
Cannot get wake-on-lan settings: No such device
Cannot get message level: No such device
Cannot get link status: No such device
Settings for %DP:
No data available

```
```

ethtool: bad command line argument(s)
For more information run ethtool -h

```
## sudo lldpcli show statistics
```

-------------------------------------------------------------------------------
LLDP statistics:
-------------------------------------------------------------------------------
Interface:    eth1
  Transmitted:  200
  Received:     0
  Discarded:    0
  Unrecognized: 0
  Ageout:       0
  Inserted:     0
  Deleted:      0
-------------------------------------------------------------------------------
Interface:    eth2
  Transmitted:  204
  Received:     203
  Discarded:    0
  Unrecognized: 0
  Ageout:       0
  Inserted:     1
  Deleted:      0
-------------------------------------------------------------------------------
Interface:    eth3
  Transmitted:  204
  Received:     203
  Discarded:    0
  Unrecognized: 0
  Ageout:       0
  Inserted:     1
  Deleted:      0
-------------------------------------------------------------------------------

```
```

lldpcli: invalid option -- '-'
Usage:   lldpcli [OPTIONS ...] [COMMAND ...]
Version: lldpd 2017-11-29

-d          Enable more debugging information.
-u socket   Specify the Unix-domain socket used for communication with lldpd(8).
-f format   Choose output format (plain, keyvalue, json, xml).
-c conf     Read the provided configuration file.

see manual page lldpcli(8) for more information

-------------------------------------------------------------------------------
LLDP statistics:
-------------------------------------------------------------------------------
Interface:    eth1
  Transmitted:  200
  Received:     0
  Discarded:    0
  Unrecognized: 0
  Ageout:       0
  Inserted:     0
  Deleted:      0
-------------------------------------------------------------------------------
Interface:    eth2
  Transmitted:  204
  Received:     203
  Discarded:    0
  Unrecognized: 0
  Ageout:       0
  Inserted:     1
  Deleted:      0
-------------------------------------------------------------------------------
Interface:    eth3
  Transmitted:  204
  Received:     203
  Discarded:    0
  Unrecognized: 0
  Ageout:       0
  Inserted:     1
  Deleted:      0
-------------------------------------------------------------------------------

```
## sudo lldpcli show neighbors
```

-------------------------------------------------------------------------------
LLDP neighbors:
-------------------------------------------------------------------------------
Interface:    eth2, via: LLDP, RID: 1, Time: 0 day, 01:39:39
  Chassis:     
    ChassisID:    mac 44:38:39:00:02:00
    SysName:      leaf01
    SysDescr:     Cumulus Linux version 3.6.1 running on Bochs Bochs
    MgmtIP:       10.0.0.11
    MgmtIP:       fd00::11
    Capability:   Bridge, off
    Capability:   Router, on
  Port:        
    PortID:       ifname swp44
    PortDescr:    swp44
    TTL:          120
-------------------------------------------------------------------------------
Interface:    eth3, via: LLDP, RID: 2, Time: 0 day, 01:39:39
  Chassis:     
    ChassisID:    mac 44:38:39:00:03:00
    SysName:      leaf02
    SysDescr:     Cumulus Linux version 3.6.1 running on Bochs Bochs
    MgmtIP:       10.0.0.12
    MgmtIP:       fd00::12
    Capability:   Bridge, off
    Capability:   Router, on
  Port:        
    PortID:       ifname swp44
    PortDescr:    swp44
    TTL:          120
-------------------------------------------------------------------------------

```
```

lldpcli: invalid option -- '-'
Usage:   lldpcli [OPTIONS ...] [COMMAND ...]
Version: lldpd 2017-11-29

-d          Enable more debugging information.
-u socket   Specify the Unix-domain socket used for communication with lldpd(8).
-f format   Choose output format (plain, keyvalue, json, xml).
-c conf     Read the provided configuration file.

see manual page lldpcli(8) for more information

-------------------------------------------------------------------------------
LLDP neighbors:
-------------------------------------------------------------------------------
Interface:    eth2, via: LLDP, RID: 1, Time: 0 day, 01:39:39
  Chassis:     
    ChassisID:    mac 44:38:39:00:02:00
    SysName:      leaf01
    SysDescr:     Cumulus Linux version 3.6.1 running on Bochs Bochs
    MgmtIP:       10.0.0.11
    MgmtIP:       fd00::11
    Capability:   Bridge, off
    Capability:   Router, on
  Port:        
    PortID:       ifname swp44
    PortDescr:    swp44
    TTL:          120
-------------------------------------------------------------------------------
Interface:    eth3, via: LLDP, RID: 2, Time: 0 day, 01:39:39
  Chassis:     
    ChassisID:    mac 44:38:39:00:03:00
    SysName:      leaf02
    SysDescr:     Cumulus Linux version 3.6.1 running on Bochs Bochs
    MgmtIP:       10.0.0.12
    MgmtIP:       fd00::12
    Capability:   Bridge, off
    Capability:   Router, on
  Port:        
    PortID:       ifname swp44
    PortDescr:    swp44
    TTL:          120
-------------------------------------------------------------------------------

```
## sensors -f
```

cumulus_vx_cpld-isa-0000
Adapter: ISA adapter
fan1:        2500 RPM  (min = 2500 RPM, max = 29000 RPM)
fan2:        2500 RPM  (min = 2500 RPM, max = 29000 RPM)
fan3:        2500 RPM  (min = 2500 RPM, max = 29000 RPM)
fan4:        2500 RPM  (min = 2500 RPM, max = 29000 RPM)
fan5:        2500 RPM  (min = 2500 RPM, max = 29000 RPM)
fan6:        2500 RPM  (min = 2500 RPM, max = 29000 RPM)
fan7:        2500 RPM  (min = 2500 RPM, max = 29000 RPM)
fan8:        2500 RPM  (min = 2500 RPM, max = 29000 RPM)
temp1:        +77.0°F  (low  = +41.0°F, high = +176.0°F)
                       (crit low = +32.0°F, crit = +185.0°F)
temp2:        +77.0°F  (low  = +41.0°F, high = +176.0°F)
                       (crit low = +32.0°F, crit = +185.0°F)
temp3:        +77.0°F  (low  = +41.0°F, high = +176.0°F)
                       (crit low = +32.0°F, crit = +185.0°F)
temp4:        +77.0°F  (low  = +41.0°F, high = +176.0°F)
                       (crit low = +32.0°F, crit = +185.0°F)
temp5:        +77.0°F  (low  = +41.0°F, high = +176.0°F)
                       (crit low = +32.0°F, crit = +185.0°F)
temp6:        +77.0°F  (low  = +41.0°F, high = +176.0°F)
                       (crit low = +32.0°F, crit = +185.0°F)
temp7:        +77.0°F  (low  = +41.0°F, high = +176.0°F)
                       (crit low = +32.0°F, crit = +185.0°F)


```
```

Usage: sensors [OPTION]... [CHIP]...
  -c, --config-file     Specify a config file
  -h, --help            Display this help text
  -s, --set             Execute `set' statements (root only)
  -f, --fahrenheit      Show temperatures in degrees fahrenheit
  -A, --no-adapter      Do not show adapter for each chip
      --bus-list        Generate bus statements for sensors.conf
  -u                    Raw output
  -v, --version         Display the program version

Use `-' after `-c' to read the config file from stdin.
If no chips are specified, all chip info will be printed.
Example chip names:
	lm78-i2c-0-2d	*-i2c-0-2d
	lm78-i2c-0-*	*-i2c-0-*
	lm78-i2c-*-2d	*-i2c-*-2d
	lm78-i2c-*-*	*-i2c-*-*
	lm78-isa-0290	*-isa-0290
	lm78-isa-*	*-isa-*
	lm78-*

```
## sudo lldpcli show statistics summary
```

-------------------------------------------------------------------------------
LLDP Global statistics:
-------------------------------------------------------------------------------
Summary of stats:
  Transmitted:  608
  Received:     406
  Discarded:    0
  Unrecognized: 0
  Ageout:       0
  Inserted:     2
  Deleted:      0
-------------------------------------------------------------------------------

```
```

lldpcli: invalid option -- '-'
Usage:   lldpcli [OPTIONS ...] [COMMAND ...]
Version: lldpd 2017-11-29

-d          Enable more debugging information.
-u socket   Specify the Unix-domain socket used for communication with lldpd(8).
-f format   Choose output format (plain, keyvalue, json, xml).
-c conf     Read the provided configuration file.

see manual page lldpcli(8) for more information

-------------------------------------------------------------------------------
LLDP Global statistics:
-------------------------------------------------------------------------------
Summary of stats:
  Transmitted:  608
  Received:     406
  Discarded:    0
  Unrecognized: 0
  Ageout:       0
  Inserted:     2
  Deleted:      0
-------------------------------------------------------------------------------

```
## sudo lldpcli show running-configuration
```

-------------------------------------------------------------------------------
Global configuration:
-------------------------------------------------------------------------------
Configuration:
  Transmit delay: 30
  Transmit hold: 4
  Receive mode: no
  Pattern for management addresses: (none)
  Interface pattern: swp*,eth*,!eth0
  Interface pattern blacklist: (none)
  Interface pattern for chassis ID: (none)
  Override description with: (none)
  Override platform with: Linux
  Override system name with: (none)
  Advertise version: yes
  Update interface descriptions: no
  Promiscuous mode on managed interfaces: no
  Disable LLDP-MED inventory: no
  LLDP-MED fast start mechanism: yes
  LLDP-MED fast start interval: 1
  Source MAC for LLDP frames on bond slaves: local
  Port ID TLV subtype for LLDP frames: ifname
  Agent type:   unknown
-------------------------------------------------------------------------------

```
```

lldpcli: invalid option -- '-'
Usage:   lldpcli [OPTIONS ...] [COMMAND ...]
Version: lldpd 2017-11-29

-d          Enable more debugging information.
-u socket   Specify the Unix-domain socket used for communication with lldpd(8).
-f format   Choose output format (plain, keyvalue, json, xml).
-c conf     Read the provided configuration file.

see manual page lldpcli(8) for more information

-------------------------------------------------------------------------------
Global configuration:
-------------------------------------------------------------------------------
Configuration:
  Transmit delay: 30
  Transmit hold: 4
  Receive mode: no
  Pattern for management addresses: (none)
  Interface pattern: swp*,eth*,!eth0
  Interface pattern blacklist: (none)
  Interface pattern for chassis ID: (none)
  Override description with: (none)
  Override platform with: Linux
  Override system name with: (none)
  Advertise version: yes
  Update interface descriptions: no
  Promiscuous mode on managed interfaces: no
  Disable LLDP-MED inventory: no
  LLDP-MED fast start mechanism: yes
  LLDP-MED fast start interval: 1
  Source MAC for LLDP frames on bond slaves: local
  Port ID TLV subtype for LLDP frames: ifname
  Agent type:   unknown
-------------------------------------------------------------------------------

```
