# Software and Licenses
## cat /etc/lsb-release
```

DISTRIB_ID="Cumulus Linux"
DISTRIB_RELEASE=3.5.3
DISTRIB_DESCRIPTION="Cumulus Linux 3.5.3"

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

DISTRIB_ID="Cumulus Linux"
DISTRIB_RELEASE=3.5.3
DISTRIB_DESCRIPTION="Cumulus Linux 3.5.3"

```
## cat /etc/os-release
```

NAME="Cumulus Linux"
VERSION_ID=3.5.3
VERSION="Cumulus Linux 3.5.3"
PRETTY_NAME="Cumulus Linux"
ID=cumulus-linux
ID_LIKE=debian
CPE_NAME=cpe:/o:cumulusnetworks:cumulus_linux:3.5.3
HOME_URL="http://www.cumulusnetworks.com/"
SUPPORT_URL="http://support.cumulusnetworks.com/"

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

NAME="Cumulus Linux"
VERSION_ID=3.5.3
VERSION="Cumulus Linux 3.5.3"
PRETTY_NAME="Cumulus Linux"
ID=cumulus-linux
ID_LIKE=debian
CPE_NAME=cpe:/o:cumulusnetworks:cumulus_linux:3.5.3
HOME_URL="http://www.cumulusnetworks.com/"
SUPPORT_URL="http://support.cumulusnetworks.com/"

```
## onie-select -d
```

Boot mode: Cumulus Linux

```
```

nohup: failed to run command ‘onie-select’: No such file or directory

```
## decode-syseeprom
```

TlvInfo Header:
   Id String:    TlvInfo
   Version:      1
   Total Length: 69
TLV Name             Code Len Value
-------------------- ---- --- -----
Vendor Name          0x2D  16 Cumulus Networks
Product Name         0x21   2 VX
Device Version       0x26   1 3
Part Number          0x22   5 3.5.3
MAC Addresses        0x2A   2 4
Base MAC Address     0x24   6 44:38:39:00:01:00
Serial Number        0x23  17 44:38:39:00:01:00
CRC-32               0xFE   4 0x19447E39
(checksum valid)

```
```

nohup: failed to run command ‘decode-syseeprom’: No such file or directory

```
## dmesg
```

[    0.000000] Initializing cgroup subsys cpuset
[    0.000000] Initializing cgroup subsys cpu
[    0.000000] Initializing cgroup subsys cpuacct
[    0.000000] Linux version 4.1.0-cl-6-amd64 (dev-support@cumulusnetworks.com) (gcc version 4.9.2 (Debian 4.9.2-10) ) #1 SMP Cumulus 4.1.33-1+cl3u12 (2018-02-25)
[    0.000000] Command line: BOOT_IMAGE=/boot/vmlinuz-4.1.0-cl-6-amd64 root=UUID=77e5d5f6-9568-4559-8513-aaf6e20d1b5f ro cl_platform=cumulus_vx console=ttyS0,115200n8 console=tty0 quiet
[    0.000000] e820: BIOS-provided physical RAM map:
[    0.000000] BIOS-e820: [mem 0x0000000000000000-0x000000000009fbff] usable
[    0.000000] BIOS-e820: [mem 0x000000000009fc00-0x000000000009ffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000000f0000-0x00000000000fffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000000100000-0x00000000bffddfff] usable
[    0.000000] BIOS-e820: [mem 0x00000000bffde000-0x00000000bfffffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000feffc000-0x00000000feffffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fffc0000-0x00000000ffffffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000100000000-0x00000002bfffffff] usable
[    0.000000] NX (Execute Disable) protection: active
[    0.000000] SMBIOS 2.8 present.
[    0.000000] DMI: Bochs Bochs, BIOS Bochs 
[    0.000000] e820: update [mem 0x00000000-0x00000fff] usable ==> reserved
[    0.000000] e820: remove [mem 0x000a0000-0x000fffff] usable
[    0.000000] e820: last_pfn = 0x2c0000 max_arch_pfn = 0x400000000
[    0.000000] MTRR default type: write-back
[    0.000000] MTRR fixed ranges enabled:
[    0.000000]   00000-9FFFF write-back
[    0.000000]   A0000-BFFFF uncachable
[    0.000000]   C0000-FFFFF write-protect
[    0.000000] MTRR variable ranges enabled:
[    0.000000]   0 base 00C0000000 mask FFC0000000 uncachable
[    0.000000]   1 disabled
[    0.000000]   2 disabled
[    0.000000]   3 disabled
[    0.000000]   4 disabled
[    0.000000]   5 disabled
[    0.000000]   6 disabled
[    0.000000]   7 disabled
[    0.000000] e820: last_pfn = 0xbffde max_arch_pfn = 0x400000000
[    0.000000] found SMP MP-table at [mem 0x000f6a60-0x000f6a6f] mapped at [ffff8800000f6a60]
[    0.000000] Base memory trampoline at [ffff880000099000] 99000 size 24576
[    0.000000] init_memory_mapping: [mem 0x00000000-0x000fffff]
[    0.000000]  [mem 0x00000000-0x000fffff] page 4k
[    0.000000] BRK [0x02011000, 0x02011fff] PGTABLE
[    0.000000] BRK [0x02012000, 0x02012fff] PGTABLE
[    0.000000] BRK [0x02013000, 0x02013fff] PGTABLE
[    0.000000] init_memory_mapping: [mem 0x2bfe00000-0x2bfffffff]
[    0.000000]  [mem 0x2bfe00000-0x2bfffffff] page 2M
[    0.000000] BRK [0x02014000, 0x02014fff] PGTABLE
[    0.000000] init_memory_mapping: [mem 0x2a0000000-0x2bfdfffff]
[    0.000000]  [mem 0x2a0000000-0x2bfdfffff] page 2M
[    0.000000] init_memory_mapping: [mem 0x00100000-0xbffddfff]
[    0.000000]  [mem 0x00100000-0x001fffff] page 4k
[    0.000000]  [mem 0x00200000-0xbfdfffff] page 2M
[    0.000000]  [mem 0xbfe00000-0xbffddfff] page 4k
[    0.000000] init_memory_mapping: [mem 0x100000000-0x29fffffff]
[    0.000000]  [mem 0x100000000-0x29fffffff] page 2M
[    0.000000] BRK [0x02015000, 0x02015fff] PGTABLE
[    0.000000] BRK [0x02016000, 0x02016fff] PGTABLE
[    0.000000] RAMDISK: [mem 0x3756e000-0x37aaefff]
[    0.000000] ACPI: Early table checksum verification disabled
[    0.000000] ACPI: RSDP 0x00000000000F6860 000014 (v00 BOCHS )
[    0.000000] ACPI: RSDT 0x00000000BFFE18D9 000034 (v01 BOCHS  BXPCRSDT 00000001 BXPC 00000001)
[    0.000000] ACPI: FACP 0x00000000BFFE0E65 000074 (v01 BOCHS  BXPCFACP 00000001 BXPC 00000001)
[    0.000000] ACPI: DSDT 0x00000000BFFE0040 000E25 (v01 BOCHS  BXPCDSDT 00000001 BXPC 00000001)
[    0.000000] ACPI: FACS 0x00000000BFFE0000 000040
[    0.000000] ACPI: SSDT 0x00000000BFFE0ED9 000948 (v01 BOCHS  BXPCSSDT 00000001 BXPC 00000001)
[    0.000000] ACPI: APIC 0x00000000BFFE1821 000080 (v01 BOCHS  BXPCAPIC 00000001 BXPC 00000001)
[    0.000000] ACPI: HPET 0x00000000BFFE18A1 000038 (v01 BOCHS  BXPCHPET 00000001 BXPC 00000001)
[    0.000000] ACPI: Local APIC address 0xfee00000
[    0.000000]  [ffffea0000000000-ffffea000affffff] PMD -> [ffff8802b5600000-ffff8802bf5fffff] on node 0
[    0.000000] Zone ranges:
[    0.000000]   DMA      [mem 0x0000000000001000-0x0000000000ffffff]
[    0.000000]   DMA32    [mem 0x0000000001000000-0x00000000ffffffff]
[    0.000000]   Normal   [mem 0x0000000100000000-0x00000002bfffffff]
[    0.000000] Movable zone start for each node
[    0.000000] Early memory node ranges
[    0.000000]   node   0: [mem 0x0000000000001000-0x000000000009efff]
[    0.000000]   node   0: [mem 0x0000000000100000-0x00000000bffddfff]
[    0.000000]   node   0: [mem 0x0000000100000000-0x00000002bfffffff]
[    0.000000] Initmem setup node 0 [mem 0x0000000000001000-0x00000002bfffffff]
[    0.000000] On node 0 totalpages: 2621308
[    0.000000]   DMA zone: 64 pages used for memmap
[    0.000000]   DMA zone: 21 pages reserved
[    0.000000]   DMA zone: 3998 pages, LIFO batch:0
[    0.000000]   DMA32 zone: 12224 pages used for memmap
[    0.000000]   DMA32 zone: 782302 pages, LIFO batch:31
[    0.000000]   Normal zone: 28672 pages used for memmap
[    0.000000]   Normal zone: 1835008 pages, LIFO batch:31
[    0.000000] ACPI: PM-Timer IO Port: 0x608
[    0.000000] ACPI: Local APIC address 0xfee00000
[    0.000000] ACPI: LAPIC_NMI (acpi_id[0xff] dfl dfl lint[0x1])
[    0.000000] IOAPIC[0]: apic_id 0, version 17, address 0xfec00000, GSI 0-23
[    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 0 global_irq 2 dfl dfl)
[    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 5 global_irq 5 high level)
[    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 9 global_irq 9 high level)
[    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 10 global_irq 10 high level)
[    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 11 global_irq 11 high level)
[    0.000000] ACPI: IRQ0 used by override.
[    0.000000] ACPI: IRQ5 used by override.
[    0.000000] ACPI: IRQ9 used by override.
[    0.000000] ACPI: IRQ10 used by override.
[    0.000000] ACPI: IRQ11 used by override.
[    0.000000] Using ACPI (MADT) for SMP configuration information
[    0.000000] ACPI: HPET id: 0x8086a201 base: 0xfed00000
[    0.000000] smpboot: Allowing 2 CPUs, 0 hotplug CPUs
[    0.000000] e820: [mem 0xc0000000-0xfeffbfff] available for PCI devices
[    0.000000] clocksource refined-jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 1910969940391419 ns
[    0.000000] eda-debug:eda_init(): size & alignment came from: compiled in defaults
[    0.000000] eda: dma_vaddr: 0xffff8800bbf00000, dma_paddr: 0x00000000bbf00000, size: 0x04000000, alignment: 0x00100000
[    0.000000] setup_percpu: NR_CPUS:256 nr_cpumask_bits:256 nr_cpu_ids:2 nr_node_ids:1
[    0.000000] PERCPU: Embedded 33 pages/cpu @ffff8802bfc00000 s94936 r8192 d32040 u1048576
[    0.000000] pcpu-alloc: s94936 r8192 d32040 u1048576 alloc=1*2097152
[    0.000000] pcpu-alloc: [0] 0 1 
[    0.000000] Built 1 zonelists in Zone order, mobility grouping on.  Total pages: 2580327
[    0.000000] Kernel command line: BOOT_IMAGE=/boot/vmlinuz-4.1.0-cl-6-amd64 root=UUID=77e5d5f6-9568-4559-8513-aaf6e20d1b5f ro cl_platform=cumulus_vx console=ttyS0,115200n8 console=tty0 quiet
[    0.000000] PID hash table entries: 4096 (order: 3, 32768 bytes)
[    0.000000] Dentry cache hash table entries: 2097152 (order: 12, 16777216 bytes)
[    0.000000] Inode-cache hash table entries: 1048576 (order: 11, 8388608 bytes)
[    0.000000] Memory: 10142848K/10485232K available (7477K kernel code, 1284K rwdata, 2412K rodata, 1208K init, 1632K bss, 342384K reserved, 0K cma-reserved)
[    0.000000] Hierarchical RCU implementation.
[    0.000000] 	RCU dyntick-idle grace-period acceleration is enabled.
[    0.000000] 	Additional per-CPU info printed with stalls.
[    0.000000] 	RCU restricting CPUs from NR_CPUS=256 to nr_cpu_ids=2.
[    0.000000] RCU: Adjusting geometry for rcu_fanout_leaf=16, nr_cpu_ids=2
[    0.000000] NR_IRQS:16640 nr_irqs:440 16
[    0.000000] Console: colour VGA+ 80x25
[    0.000000] console [tty0] enabled
[    0.000000] console [ttyS0] enabled
[    0.000000] clocksource hpet: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 19112604467 ns
[    0.000000] hpet clockevent registered
[    0.000000] tsc: Fast TSC calibration failed
[    0.000000] tsc: Unable to calibrate against PIT
[    0.000000] tsc: HPET/PMTIMER calibration failed
[    0.000000] tsc: Marking TSC unstable due to could not calculate TSC khz
[    0.006000] Calibrating delay loop... 2072.57 BogoMIPS (lpj=1036288)
[    0.012000] pid_max: default: 32768 minimum: 301
[    0.012000] ACPI: Core revision 20150410
[    0.018000] ACPI: All ACPI Tables successfully acquired
[    0.019000] Mount-cache hash table entries: 32768 (order: 6, 262144 bytes)
[    0.019000] Mountpoint-cache hash table entries: 32768 (order: 6, 262144 bytes)
[    0.028000] Initializing cgroup subsys blkio
[    0.028000] Initializing cgroup subsys memory
[    0.029000] Initializing cgroup subsys devices
[    0.029000] Initializing cgroup subsys freezer
[    0.029000] Initializing cgroup subsys net_cls
[    0.029000] Initializing cgroup subsys perf_event
[    0.029000] Initializing cgroup subsys net_prio
[    0.029000] Initializing cgroup subsys hugetlb
[    0.029000] Initializing cgroup subsys l3mdev
[    0.032000] mce: CPU supports 10 MCE banks
[    0.033000] Last level iTLB entries: 4KB 0, 2MB 0, 4MB 0
[    0.033000] Last level dTLB entries: 4KB 0, 2MB 0, 4MB 0, 1GB 0
[    0.079000] Freeing SMP alternatives memory: 28K (ffffffff81e71000 - ffffffff81e78000)
[    0.079000] ftrace: allocating 26718 entries in 105 pages
[    0.096000] x2apic: IRQ remapping doesn't support X2APIC mode
[    0.112000] ..TIMER: vector=0x30 apic1=0 pin1=2 apic2=-1 pin2=-1
[    0.117000] APIC calibration not consistent with PM-Timer: 106ms instead of 100ms
[    0.117000] APIC delta adjusted to PM-Timer: 6248577 (6627485)
[    0.117000] smpboot: CPU0: Intel(R) Core(TM)2 Duo CPU     T7700  @ 2.40GHz (fam: 06, model: 0f, stepping: 0b)
[    0.117000] Performance Events: unsupported p6 CPU model 15 no PMU driver, software events only.
[    0.126000] NMI watchdog: disabled (cpu0): hardware events not enabled
[    0.126000] NMI watchdog: Shutting down hard lockup detector on all cpus
[    0.130000] x86: Booting SMP configuration:
[    0.130000] .... node  #0, CPUs:      #1
[    0.156000] x86: Booted up 1 node, 2 CPUs
[    0.156000] smpboot: Total of 2 processors activated (4431.87 BogoMIPS)
[    0.169000] devtmpfs: initialized
[    0.176000] clocksource jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 1911260446275000 ns
[    0.181000] NET: Registered protocol family 16
[    0.188000] cpuidle: using governor ladder
[    0.194000] cpuidle: using governor menu
[    0.194000] ACPI: bus type PCI registered
[    0.194000] acpiphp: ACPI Hot Plug PCI Controller Driver version: 0.5
[    0.195000] PCI: Using configuration type 1 for base access
[    0.225000] ACPI: Added _OSI(Module Device)
[    0.225000] ACPI: Added _OSI(Processor Device)
[    0.225000] ACPI: Added _OSI(3.0 _SCP Extensions)
[    0.225000] ACPI: Added _OSI(Processor Aggregator Device)
[    0.230000] ACPI: Interpreter enabled
[    0.230000] ACPI: (supports S0 S5)
[    0.230000] ACPI: Using IOAPIC for interrupt routing
[    0.230000] PCI: Using host bridge windows from ACPI; if necessary, use "pci=nocrs" and report a bug
[    0.247000] ACPI: PCI Root Bridge [PCI0] (domain 0000 [bus 00-ff])
[    0.247000] acpi PNP0A03:00: _OSC: OS supports [ASPM ClockPM Segments MSI]
[    0.247000] acpi PNP0A03:00: _OSC failed (AE_NOT_FOUND); disabling ASPM
[    0.247000] acpi PNP0A03:00: fail to add MMCONFIG information, can't access extended PCI configuration space under this bridge.
[    0.247000] acpiphp: Slot [3] registered
[    0.248000] acpiphp: Slot [4] registered
[    0.248000] acpiphp: Slot [5] registered
[    0.248000] acpiphp: Slot [6] registered
[    0.248000] acpiphp: Slot [7] registered
[    0.248000] acpiphp: Slot [8] registered
[    0.249000] acpiphp: Slot [9] registered
[    0.249000] acpiphp: Slot [10] registered
[    0.249000] acpiphp: Slot [11] registered
[    0.249000] acpiphp: Slot [12] registered
[    0.249000] acpiphp: Slot [13] registered
[    0.250000] acpiphp: Slot [14] registered
[    0.250000] acpiphp: Slot [15] registered
[    0.250000] acpiphp: Slot [16] registered
[    0.251000] acpiphp: Slot [17] registered
[    0.251000] acpiphp: Slot [18] registered
[    0.251000] acpiphp: Slot [19] registered
[    0.251000] acpiphp: Slot [20] registered
[    0.252000] acpiphp: Slot [21] registered
[    0.252000] acpiphp: Slot [22] registered
[    0.252000] acpiphp: Slot [23] registered
[    0.252000] acpiphp: Slot [24] registered
[    0.252000] acpiphp: Slot [25] registered
[    0.252000] acpiphp: Slot [26] registered
[    0.252000] acpiphp: Slot [27] registered
[    0.253000] acpiphp: Slot [28] registered
[    0.253000] acpiphp: Slot [29] registered
[    0.253000] acpiphp: Slot [30] registered
[    0.253000] acpiphp: Slot [31] registered
[    0.253000] PCI host bridge to bus 0000:00
[    0.253000] pci_bus 0000:00: root bus resource [bus 00-ff]
[    0.253000] pci_bus 0000:00: root bus resource [io  0x0000-0x0cf7 window]
[    0.253000] pci_bus 0000:00: root bus resource [io  0x0d00-0xadff window]
[    0.253000] pci_bus 0000:00: root bus resource [io  0xae0f-0xaeff window]
[    0.253000] pci_bus 0000:00: root bus resource [io  0xaf20-0xafdf window]
[    0.253000] pci_bus 0000:00: root bus resource [io  0xafe4-0xffff window]
[    0.253000] pci_bus 0000:00: root bus resource [mem 0x000a0000-0x000bffff window]
[    0.253000] pci_bus 0000:00: root bus resource [mem 0xc0000000-0xfebfffff window]
[    0.254000] pci 0000:00:00.0: [8086:1237] type 00 class 0x060000
[    0.257000] pci 0000:00:01.0: [8086:7000] type 00 class 0x060100
[    0.262000] pci 0000:00:01.1: [8086:7010] type 00 class 0x010180
[    0.272000] pci 0000:00:01.1: reg 0x20: [io  0xc0c0-0xc0cf]
[    0.276000] pci 0000:00:01.1: legacy IDE quirk: reg 0x10: [io  0x01f0-0x01f7]
[    0.276000] pci 0000:00:01.1: legacy IDE quirk: reg 0x14: [io  0x03f6]
[    0.276000] pci 0000:00:01.1: legacy IDE quirk: reg 0x18: [io  0x0170-0x0177]
[    0.276000] pci 0000:00:01.1: legacy IDE quirk: reg 0x1c: [io  0x0376]
[    0.278000] pci 0000:00:01.3: [8086:7113] type 00 class 0x068000
[    0.283000] pci 0000:00:01.3: quirk: [io  0x0600-0x063f] claimed by PIIX4 ACPI
[    0.283000] pci 0000:00:01.3: quirk: [io  0x0700-0x070f] claimed by PIIX4 SMB
[    0.286000] pci 0000:00:02.0: [1013:00b8] type 00 class 0x030000
[    0.292000] pci 0000:00:02.0: reg 0x10: [mem 0xfc000000-0xfdffffff pref]
[    0.303000] pci 0000:00:02.0: reg 0x14: [mem 0xfebf0000-0xfebf0fff]
[    0.341000] pci 0000:00:02.0: reg 0x30: [mem 0xfebe0000-0xfebeffff pref]
[    0.360000] pci 0000:00:03.0: [1af4:1000] type 00 class 0x020000
[    0.362000] pci 0000:00:03.0: reg 0x10: [io  0xc040-0xc05f]
[    0.364000] pci 0000:00:03.0: reg 0x14: [mem 0xfebf1000-0xfebf1fff]
[    0.382000] pci 0000:00:04.0: [1af4:1000] type 00 class 0x020000
[    0.386000] pci 0000:00:04.0: reg 0x10: [io  0xc060-0xc07f]
[    0.390000] pci 0000:00:04.0: reg 0x14: [mem 0xfebf2000-0xfebf2fff]
[    0.406000] pci 0000:00:05.0: [1af4:1000] type 00 class 0x020000
[    0.409000] pci 0000:00:05.0: reg 0x10: [io  0xc080-0xc09f]
[    0.412000] pci 0000:00:05.0: reg 0x14: [mem 0xfebf3000-0xfebf3fff]
[    0.429000] pci 0000:00:06.0: [1af4:1000] type 00 class 0x020000
[    0.432000] pci 0000:00:06.0: reg 0x10: [io  0xc0a0-0xc0bf]
[    0.435000] pci 0000:00:06.0: reg 0x14: [mem 0xfebf4000-0xfebf4fff]
[    0.452000] pci 0000:00:07.0: [1af4:1001] type 00 class 0x010000
[    0.455000] pci 0000:00:07.0: reg 0x10: [io  0xc000-0xc03f]
[    0.457000] pci 0000:00:07.0: reg 0x14: [mem 0xfebf5000-0xfebf5fff]
[    0.474000] pci_bus 0000:00: on NUMA node 0
[    0.482000] ACPI: PCI Interrupt Link [LNKA] (IRQs 5 *10 11)
[    0.482000] ACPI: PCI Interrupt Link [LNKB] (IRQs 5 *10 11)
[    0.483000] ACPI: PCI Interrupt Link [LNKC] (IRQs 5 10 *11)
[    0.483000] ACPI: PCI Interrupt Link [LNKD] (IRQs 5 10 *11)
[    0.484000] ACPI: PCI Interrupt Link [LNKS] (IRQs *9)
[    0.487000] ACPI: Enabled 16 GPEs in block 00 to 0F
[    0.503000] SCSI subsystem initialized
[    0.511000] libata version 3.00 loaded.
[    0.513000] ACPI: bus type USB registered
[    0.514000] usbcore: registered new interface driver usbfs
[    0.514000] usbcore: registered new interface driver hub
[    0.515000] usbcore: registered new device driver usb
[    0.516000] pps_core: LinuxPPS API ver. 1 registered
[    0.516000] pps_core: Software ver. 5.3.6 - Copyright 2005-2007 Rodolfo Giometti <giometti@linux.it>
[    0.516000] PTP clock support registered
[    0.516000] EDAC MC: Ver: 3.0.0
[    0.524000] PCI: Using ACPI for IRQ routing
[    0.524000] PCI: pci_cache_line_size set to 64 bytes
[    0.526000] e820: reserve RAM buffer [mem 0x0009fc00-0x0009ffff]
[    0.526000] e820: reserve RAM buffer [mem 0xbffde000-0xbfffffff]
[    0.539000] HPET: 3 timers in total, 0 timers will be used for per-cpu timer
[    0.541000] amd_nb: Cannot enumerate AMD northbridges
[    0.542000] Switched to clocksource hpet
[    1.170274] pnp: PnP ACPI init
[    1.175223] pnp 00:00: Plug and Play ACPI device, IDs PNP0b00 (active)
[    1.177270] pnp 00:01: Plug and Play ACPI device, IDs PNP0303 (active)
[    1.177270] pnp 00:02: Plug and Play ACPI device, IDs PNP0f13 (active)
[    1.178232] pnp 00:03: [dma 2]
[    1.178232] pnp 00:03: Plug and Play ACPI device, IDs PNP0700 (active)
[    1.179269] pnp 00:04: Plug and Play ACPI device, IDs PNP0400 (active)
[    1.180263] pnp 00:05: Plug and Play ACPI device, IDs PNP0501 (active)
[    1.181324] pnp: PnP ACPI: found 6 devices
[    1.311242] clocksource acpi_pm: mask: 0xffffff max_cycles: 0xffffff, max_idle_ns: 2085701024 ns
[    1.312263] pci_bus 0000:00: resource 4 [io  0x0000-0x0cf7 window]
[    1.312263] pci_bus 0000:00: resource 5 [io  0x0d00-0xadff window]
[    1.312263] pci_bus 0000:00: resource 6 [io  0xae0f-0xaeff window]
[    1.312263] pci_bus 0000:00: resource 7 [io  0xaf20-0xafdf window]
[    1.312263] pci_bus 0000:00: resource 8 [io  0xafe4-0xffff window]
[    1.312263] pci_bus 0000:00: resource 9 [mem 0x000a0000-0x000bffff window]
[    1.312263] pci_bus 0000:00: resource 10 [mem 0xc0000000-0xfebfffff window]
[    1.316272] NET: Registered protocol family 2
[    1.332254] TCP established hash table entries: 131072 (order: 8, 1048576 bytes)
[    1.353239] TCP bind hash table entries: 65536 (order: 8, 1048576 bytes)
[    1.373266] TCP: Hash tables configured (established 131072 bind 65536)
[    1.377219] UDP hash table entries: 8192 (order: 6, 262144 bytes)
[    1.386333] UDP-Lite hash table entries: 8192 (order: 6, 262144 bytes)
[    1.399280] NET: Registered protocol family 1
[    1.409305] RPC: Registered named UNIX socket transport module.
[    1.409305] RPC: Registered udp transport module.
[    1.409305] RPC: Registered tcp transport module.
[    1.409305] RPC: Registered tcp NFSv4.1 backchannel transport module.
[    1.410335] pci 0000:00:00.0: Limiting direct PCI/PCI transfers
[    1.411281] pci 0000:00:01.0: PIIX3: Enabling Passive Release
[    1.411281] pci 0000:00:01.0: Activating ISA DMA hang workarounds
[    1.411281] pci 0000:00:02.0: Video device with shadowed ROM
[    1.412314] PCI: CLS 0 bytes, default 64
[    1.421315] Trying to unpack rootfs image as initramfs...
[    3.975261] Freeing initrd memory: 5380K (ffff88003756e000 - ffff880037aaf000)
[    3.976340] PCI-DMA: Using software bounce buffering for IO (SWIOTLB)
[    3.976340] software IO TLB [mem 0xb7f00000-0xbbf00000] (64MB) mapped at [ffff8800b7f00000-ffff8800bbefffff]
[    3.998228] futex hash table entries: 512 (order: 3, 32768 bytes)
[    4.001241] audit: initializing netlink subsys (disabled)
[    4.001241] audit: type=2000 audit(1532023613.001:1): initialized
[    4.012503] HugeTLB registered 2 MB page size, pre-allocated 0 pages
[    4.020332] VFS: Disk quotas dquot_6.6.0
[    4.022257] VFS: Dquot-cache hash table entries: 512 (order 0, 4096 bytes)
[    4.040255] squashfs: version 4.0 (2009/01/31) Phillip Lougher
[    4.055256] NFS: Registering the id_resolver key type
[    4.055256] Key type id_resolver registered
[    4.055256] Key type id_legacy registered
[    4.056267] nfs4filelayout_init: NFSv4 File Layout Driver Registering...
[    4.092120] alg: No test for stdrng (krng)
[    4.092120] bounce: pool size: 64 pages
[    4.093281] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 250)
[    4.097879] io scheduler noop registered
[    4.098437] io scheduler deadline registered
[    4.098437] io scheduler cfq registered (default)
[    4.100251] pci_hotplug: PCI Hot Plug PCI Core version: 0.5
[    4.100251] pciehp: PCI Express Hot Plug Controller Driver version: 0.4
[    4.102302] input: Power Button as /devices/LNXSYSTM:00/LNXPWRBN:00/input/input0
[    4.102302] ACPI: Power Button [PWRF]
[    4.105232] GHES: HEST is not enabled!
[    4.164251] ACPI: PCI Interrupt Link [LNKC] enabled at IRQ 11
[    4.166240] virtio-pci 0000:00:03.0: virtio_pci: leaving for legacy driver
[    4.240321] ACPI: PCI Interrupt Link [LNKD] enabled at IRQ 10
[    4.241262] virtio-pci 0000:00:04.0: virtio_pci: leaving for legacy driver
[    4.297217] ACPI: PCI Interrupt Link [LNKA] enabled at IRQ 10
[    4.297217] virtio-pci 0000:00:05.0: virtio_pci: leaving for legacy driver
[    4.360268] ACPI: PCI Interrupt Link [LNKB] enabled at IRQ 11
[    4.360268] virtio-pci 0000:00:06.0: virtio_pci: leaving for legacy driver
[    4.423219] virtio-pci 0000:00:07.0: virtio_pci: leaving for legacy driver
[    4.426311] Serial: 8250/16550 driver, 4 ports, IRQ sharing enabled
[    4.465309] 00:05: ttyS0 at I/O 0x3f8 (irq = 4, base_baud = 115200) is a 16550A
[    4.492284] brd: module loaded
[    4.517408] ata_piix 0000:00:01.1: version 2.13
[    4.532883] scsi host0: ata_piix
[    4.535992] scsi host1: ata_piix
[    4.536263] ata1: PATA max MWDMA2 cmd 0x1f0 ctl 0x3f6 bmdma 0xc0c0 irq 14
[    4.536263] ata2: PATA max MWDMA2 cmd 0x170 ctl 0x376 bmdma 0xc0c8 irq 15
[    4.540215] ehci_hcd: USB 2.0 'Enhanced' Host Controller (EHCI) Driver
[    4.540215] ehci-pci: EHCI PCI platform driver
[    4.541192] ohci_hcd: USB 1.1 'Open' Host Controller (OHCI) Driver
[    4.541192] ohci-pci: OHCI PCI platform driver
[    4.541192] usbcore: registered new interface driver usb-storage
[    4.543160] usbcore: registered new interface driver usbserial
[    4.543160] usbcore: registered new interface driver usbserial_generic
[    4.543216] usbserial: USB Serial support registered for generic
[    4.544274] i8042: PNP: PS/2 Controller [PNP0303:KBD,PNP0f13:MOU] at 0x60,0x64 irq 1,12
[    4.554344] serio: i8042 KBD port at 0x60,0x64 irq 1
[    4.554344] serio: i8042 AUX port at 0x60,0x64 irq 12
[    4.556281] mousedev: PS/2 mouse device common for all mice
[    4.559233] rtc_cmos 00:00: RTC can wake from S4
[    4.560339] input: AT Translated Set 2 keyboard as /devices/platform/i8042/serio0/input/input1
[    4.565107] rtc_cmos 00:00: rtc core: registered rtc_cmos as rtc0
[    4.566282] rtc_cmos 00:00: alarms up to one day, 114 bytes nvram, hpet irqs
[    4.566282] sdhci: Secure Digital Host Controller Interface driver
[    4.566282] sdhci: Copyright(c) Pierre Ossman
[    4.566282] sdhci-pltfm: SDHCI platform and OF driver helper
[    4.567280] usbcore: registered new interface driver usbhid
[    4.567280] usbhid: USB HID core driver
[    4.570553] ip_tables: (C) 2000-2006 Netfilter Core Team
[    4.598242] NET: Registered protocol family 10
[    4.606259] NET: Registered protocol family 17
[    4.607257] NET: Registered protocol family 15
[    4.607257] Key type dns_resolver registered
[    4.620903] registered taskstats version 1
[    4.639459] rtc_cmos 00:00: setting system clock to 2018-07-19 18:06:55 UTC (1532023615)
[    4.703358] ata1.01: NODEV after polling detection
[    4.706350] ata1.00: ATA-7: QEMU HARDDISK, 2.2.1, max UDMA/100
[    4.706350] ata1.00: 536870912 sectors, multi 16: LBA48 
[    4.710882] ata1.00: configured for MWDMA2
[    4.714269] scsi 0:0:0:0: Direct-Access     ATA      QEMU HARDDISK    1    PQ: 0 ANSI: 5
[    4.717259] sd 0:0:0:0: Attached scsi generic sg0 type 0
[    4.717259] sd 0:0:0:0: [sda] 536870912 512-byte logical blocks: (275 GB/256 GiB)
[    4.718327] sd 0:0:0:0: [sda] Write Protect is off
[    4.718327] sd 0:0:0:0: [sda] Mode Sense: 00 3a 00 00
[    4.718654] sd 0:0:0:0: [sda] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
[    4.875225]  sda: sda1 sda2 sda3 sda4
[    4.876400] sd 0:0:0:0: [sda] Attached SCSI disk
[    4.909265] Freeing unused kernel memory: 1208K (ffffffff81d43000 - ffffffff81e71000)
[    4.909265] Write protecting the kernel read-only data: 12288k
[    4.927257] Freeing unused kernel memory: 704K (ffff880001750000 - ffff880001800000)
[    4.966197] Freeing unused kernel memory: 1684K (ffff880001a5b000 - ffff880001c00000)
[    5.136219] systemd-udevd[74]: starting version 215
[    5.140259] random: systemd-udevd urandom read with 34 bits of entropy available
[    5.188387] hrtimer: interrupt took 4283960 ns
[    5.770381] piix4_smbus 0000:00:01.3: SMBus Host Controller at 0x700, revision 0
[    6.183936] random: nonblocking pool is initialized
[    6.506075] device-mapper: uevent: version 1.0.3
[    6.506346] device-mapper: ioctl: 4.31.0-ioctl (2015-3-12) initialised: dm-devel@redhat.com
[    6.541260] raid6: sse2x1   gen()  6429 MB/s
[    6.558247] raid6: sse2x1   xor()  1275 MB/s
[    6.575310] raid6: sse2x2   gen()  4304 MB/s
[    6.592230] raid6: sse2x2   xor()  5435 MB/s
[    6.609207] raid6: sse2x4   gen()  9046 MB/s
[    6.626185] raid6: sse2x4   xor()  6050 MB/s
[    6.626185] raid6: using algorithm sse2x4 gen() 9046 MB/s
[    6.626185] raid6: .... xor() 6050 MB/s, rmw enabled
[    6.626185] raid6: using ssse3x2 recovery algorithm
[    6.629244] xor: measuring software checksum speed
[    6.639240]    prefetch64-sse:  7500.000 MB/sec
[    6.649251]    generic_sse:  5420.000 MB/sec
[    6.649251] xor: using function: prefetch64-sse (7500.000 MB/sec)
[    6.745009] Btrfs loaded
[    7.067800] BTRFS: device label CL-SYSTEM devid 1 transid 2677 /dev/sda4
[    7.221237] BTRFS info (device sda4): disk space caching is enabled
[    7.221237] BTRFS: has skinny extents
[   16.848199] systemd[1]: systemd 215 running in system mode. (+PAM +AUDIT +SELINUX +IMA +SYSVINIT +LIBCRYPTSETUP +GCRYPT +ACL +XZ -SECCOMP -APPARMOR)
[   16.848199] systemd[1]: Detected virtualization 'kvm'.
[   16.848199] systemd[1]: Detected architecture 'x86-64'.
[   17.414181] systemd[1]: Inserted module 'autofs4'
[   17.417973] systemd[1]: Set hostname to <oob-mgmt-server>.
[   22.303186] systemd[1]: [/lib/systemd/system/docker.service:25] Unknown lvalue 'Delegate' in section 'Service'
[   22.394267] systemd[1]: Starting Forward Password Requests to Wall Directory Watch.
[   22.395205] systemd[1]: Started Forward Password Requests to Wall Directory Watch.
[   22.395205] systemd[1]: Expecting device dev-ttyS0.device...
[   22.401198] systemd[1]: Starting Remote File Systems (Pre).
[   22.408317] systemd[1]: Reached target Remote File Systems (Pre).
[   22.408317] systemd[1]: Starting Dispatch Password Requests to Console Directory Watch.
[   22.408317] systemd[1]: Started Dispatch Password Requests to Console Directory Watch.
[   22.409196] systemd[1]: Starting Arbitrary Executable File Formats File System Automount Point.
[   22.417289] systemd[1]: Set up automount Arbitrary Executable File Formats File System Automount Point.
[   22.417289] systemd[1]: Starting Swap.
[   22.423210] systemd[1]: Reached target Swap.
[   22.424175] systemd[1]: Expecting device dev-disk-by\x2duuid-77e5d5f6\x2d9568\x2d4559\x2d8513\x2daaf6e20d1b5f.device...
[   22.430184] systemd[1]: Starting Root Slice.
[   22.437180] systemd[1]: Created slice Root Slice.
[   22.437180] systemd[1]: Starting /dev/initctl Compatibility Named Pipe.
[   22.444313] systemd[1]: Listening on /dev/initctl Compatibility Named Pipe.
[   22.444313] systemd[1]: Starting Delayed Shutdown Socket.
[   22.451192] systemd[1]: Listening on Delayed Shutdown Socket.
[   22.452175] systemd[1]: Starting Journal Socket (/dev/log).
[   22.459245] systemd[1]: Listening on Journal Socket (/dev/log).
[   22.459245] systemd[1]: Starting LVM2 metadata daemon socket.
[   22.466287] systemd[1]: Listening on LVM2 metadata daemon socket.
[   22.466287] systemd[1]: Starting Device-mapper event daemon FIFOs.
[   22.473193] systemd[1]: Listening on Device-mapper event daemon FIFOs.
[   22.473193] systemd[1]: Starting User and Session Slice.
[   22.482169] systemd[1]: Created slice User and Session Slice.
[   22.482169] systemd[1]: Starting udev Control Socket.
[   22.489210] systemd[1]: Listening on udev Control Socket.
[   22.489210] systemd[1]: Starting udev Kernel Socket.
[   22.496174] systemd[1]: Listening on udev Kernel Socket.
[   22.496174] systemd[1]: Starting Journal Socket.
[   22.503259] systemd[1]: Listening on Journal Socket.
[   22.503259] systemd[1]: Starting System Slice.
[   22.510222] systemd[1]: Created slice System Slice.
[   22.511173] systemd[1]: Starting Increase datagram queue length...
[   22.521207] systemd[1]: Mounting Huge Pages File System...
[   22.533184] systemd[1]: Mounting POSIX Message Queue File System...
[   22.542188] systemd[1]: Starting Create list of required static device nodes for the current kernel...
[   22.556199] systemd[1]: Mounted Debug File System.
[   23.054237] systemd[1]: Started Set Up Additional Binary Formats.
[   23.054237] systemd[1]: Starting udev Coldplug all Devices...
[   23.072196] systemd[1]: Starting system-getty.slice.
[   23.086425] systemd[1]: Created slice system-getty.slice.
[   23.086425] systemd[1]: Starting system-serial\x2dgetty.slice.
[   23.101413] systemd[1]: Created slice system-serial\x2dgetty.slice.
[   23.102179] systemd[1]: Starting Load Kernel Modules...
[   23.115948] systemd[1]: Starting Slices.
[   23.127167] systemd[1]: Reached target Slices.
[   23.141374] systemd[1]: Mounted POSIX Message Queue File System.
[   23.153288] systemd[1]: Mounted Huge Pages File System.
[   23.173177] systemd[1]: Started Increase datagram queue length.
[   23.191174] systemd[1]: Started Create list of required static device nodes for the current kernel.
[   23.211186] systemd[1]: Starting Create Static Device Nodes in /dev...
[   23.225191] systemd[1]: Starting Syslog Socket.
[   23.237199] systemd[1]: Listening on Syslog Socket.
[   23.238191] systemd[1]: Starting Journal Service...
[   23.270358] systemd[1]: Started Journal Service.
[   23.636174] loop: module loaded
[   24.195175] Ethernet Channel Bonding Driver: v3.7.1 (April 27, 2011)
[   24.195175] MII link monitoring set to 100 ms
[   24.201202] systemd-udevd[258]: starting version 215
[   24.532179] BTRFS info (device sda4): turning on flush-on-commit
[   24.532179] BTRFS info (device sda4): disk space caching is enabled
[   24.882232] bridge: automatic filtering via arp/ip/ip6tables has been deprecated. Update your scripts to load br_netfilter if you need this.
[   25.085207] Bridge firewalling registered
[   25.313206] tun: Universal TUN/TAP device driver, 1.6
[   25.313206] tun: (C) 1999-2004 Max Krasnyansky <maxk@qualcomm.com>
[   26.440301] cumulus_vx_platform: version 0.1 loaded
[   26.721189] softdog: Software Watchdog Timer: 0.08 initialized. soft_noboot=0 soft_margin=60 sec soft_panic=0 (nowayout=0)
[   26.990185] disallow multiple vlans in bridge
[   26.990185] disable local fdb installation
[   26.990185] set stp state - user
[   27.012183] disable multicast ignore IPv6 solicited groups
[   31.592149] systemd-journald[256]: Received request to flush runtime journal from PID 1
[   35.860965] audit: type=1305 audit(1532023646.722:2): audit_pid=363 old=0 auid=4294967295 ses=4294967295 res=1
[   38.374198] nf_conntrack version 0.5.0 (65536 buckets, 262144 max)
[   46.791202] ip6_tables: (C) 2000-2006 Netfilter Core Team
[   49.215178] Ebtables v2.0 registered
[   53.394354] ISO 9660 Extensions: Microsoft Joliet Level 3
[   53.402305] ISO 9660 Extensions: RRIP_1991A
[   54.575255] BTRFS: new size for /dev/sda4 is 255728418816
[   75.416266] Initializing XFRM netlink socket
[   75.524281] Netfilter messages via NETLINK v0.30.
[   75.545202] ctnetlink v0.93: registering with nfnetlink.
[   76.221263] IPv6: ADDRCONF(NETDEV_UP): docker0: link is not ready

```
```


Usage:
 dmesg [options]

Options:
 -C, --clear                 clear the kernel ring buffer
 -c, --read-clear            read and clear all messages
 -D, --console-off           disable printing messages to console
 -E, --console-on            enable printing messages to console
 -F, --file <file>           use the file instead of the kernel log buffer
 -f, --facility <list>       restrict output to defined facilities
 -H, --human                 human readable output
 -k, --kernel                display kernel messages
 -L, --color[=<when>]        colorize messages (auto, always or never)
 -l, --level <list>          restrict output to defined levels
 -n, --console-level <level> set level of messages printed to console
 -P, --nopager               do not pipe output into a pager
 -r, --raw                   print the raw message buffer
 -S, --syslog                force to use syslog(2) rather than /dev/kmsg
 -s, --buffer-size <size>    buffer size to query the kernel ring buffer
 -u, --userspace             display userspace messages
 -w, --follow                wait for new messages
 -x, --decode                decode facility and level to readable string
 -d, --show-delta            show time delta between printed messages
 -e, --reltime               show local time and time delta in readable format
 -T, --ctime                 show human readable timestamp
 -t, --notime                don't print messages timestamp
     --time-format <format>  show time stamp using format:
                               [delta|reltime|ctime|notime|iso]
Suspending/resume will make ctime and iso timestamps inaccurate.

 -h, --help     display this help and exit
 -V, --version  output version information and exit

Supported log facilities:
    kern - kernel messages
    user - random user-level messages
    mail - mail system
  daemon - system daemons
    auth - security/authorization messages
  syslog - messages generated internally by syslogd
     lpr - line printer subsystem
    news - network news subsystem

Supported log levels (priorities):
   emerg - system is unusable
   alert - action must be taken immediately
    crit - critical conditions
     err - error conditions
    warn - warning conditions
  notice - normal but significant condition
    info - informational
   debug - debug-level messages


For more details see dmesg(1).

```
## history
```

nohup: failed to run command ‘history’: No such file or directory

```
```

nohup: failed to run command ‘history’: No such file or directory

```
## hostname
```

oob-mgmt-server

```
```

Usage: hostname [-b] {hostname|-F file}         set host name (from file)
       hostname [-a|-A|-d|-f|-i|-I|-s|-y]       display formatted name
       hostname                                 display host name

       {yp,nis,}domainname {nisdomain|-F file}  set NIS domain name (from file)
       {yp,nis,}domainname                      display NIS domain name

       dnsdomainname                            display dns domain name

       hostname -V|--version|-h|--help          print info and exit

Program name:
       {yp,nis,}domainname=hostname -y
       dnsdomainname=hostname -d

Program options:
    -a, --alias            alias names
    -A, --all-fqdns        all long host names (FQDNs)
    -b, --boot             set default hostname if none available
    -d, --domain           DNS domain name
    -f, --fqdn, --long     long host name (FQDN)
    -F, --file             read host name or NIS domain name from given file
    -i, --ip-address       addresses for the host name
    -I, --all-ip-addresses all addresses for the host
    -s, --short            short host name
    -y, --yp, --nis        NIS/YP domain name

Description:
   This command can get or set the host name or the NIS domain name. You can
   also get the DNS domain or the FQDN (fully qualified domain name).
   Unless you are using bind or NIS for host lookups you can change the
   FQDN (Fully Qualified Domain Name) and the DNS domain name (which is
   part of the FQDN) in the /etc/hosts file.

```
## date
```

Thu Jul 19 19:47:08 UTC 2018

```
```

Usage: date [OPTION]... [+FORMAT]
  or:  date [-u|--utc|--universal] [MMDDhhmm[[CC]YY][.ss]]
Display the current time in the given FORMAT, or set the system date.

Mandatory arguments to long options are mandatory for short options too.
  -d, --date=STRING         display time described by STRING, not 'now'
  -f, --file=DATEFILE       like --date once for each line of DATEFILE
  -I[TIMESPEC], --iso-8601[=TIMESPEC]  output date/time in ISO 8601 format.
                            TIMESPEC='date' for date only (the default),
                            'hours', 'minutes', 'seconds', or 'ns' for date
                            and time to the indicated precision.
  -r, --reference=FILE      display the last modification time of FILE
  -R, --rfc-2822            output date and time in RFC 2822 format.
                            Example: Mon, 07 Aug 2006 12:34:56 -0600
      --rfc-3339=TIMESPEC   output date and time in RFC 3339 format.
                            TIMESPEC='date', 'seconds', or 'ns' for
                            date and time to the indicated precision.
                            Date and time components are separated by
                            a single space: 2006-08-07 12:34:56-06:00
  -s, --set=STRING          set time described by STRING
  -u, --utc, --universal    print or set Coordinated Universal Time (UTC)
      --help     display this help and exit
      --version  output version information and exit

FORMAT controls the output.  Interpreted sequences are:

  %%   a literal %
  %a   locale's abbreviated weekday name (e.g., Sun)
  %A   locale's full weekday name (e.g., Sunday)
  %b   locale's abbreviated month name (e.g., Jan)
  %B   locale's full month name (e.g., January)
  %c   locale's date and time (e.g., Thu Mar  3 23:05:25 2005)
  %C   century; like %Y, except omit last two digits (e.g., 20)
  %d   day of month (e.g., 01)
  %D   date; same as %m/%d/%y
  %e   day of month, space padded; same as %_d
  %F   full date; same as %Y-%m-%d
  %g   last two digits of year of ISO week number (see %G)
  %G   year of ISO week number (see %V); normally useful only with %V
  %h   same as %b
  %H   hour (00..23)
  %I   hour (01..12)
  %j   day of year (001..366)
  %k   hour, space padded ( 0..23); same as %_H
  %l   hour, space padded ( 1..12); same as %_I
  %m   month (01..12)
  %M   minute (00..59)
  %n   a newline
  %N   nanoseconds (000000000..999999999)
  %p   locale's equivalent of either AM or PM; blank if not known
  %P   like %p, but lower case
  %r   locale's 12-hour clock time (e.g., 11:11:04 PM)
  %R   24-hour hour and minute; same as %H:%M
  %s   seconds since 1970-01-01 00:00:00 UTC
  %S   second (00..60)
  %t   a tab
  %T   time; same as %H:%M:%S
  %u   day of week (1..7); 1 is Monday
  %U   week number of year, with Sunday as first day of week (00..53)
  %V   ISO week number, with Monday as first day of week (01..53)
  %w   day of week (0..6); 0 is Sunday
  %W   week number of year, with Monday as first day of week (00..53)
  %x   locale's date representation (e.g., 12/31/99)
  %X   locale's time representation (e.g., 23:13:48)
  %y   last two digits of year (00..99)
  %Y   year
  %z   +hhmm numeric time zone (e.g., -0400)
  %:z  +hh:mm numeric time zone (e.g., -04:00)
  %::z  +hh:mm:ss numeric time zone (e.g., -04:00:00)
  %:::z  numeric time zone with : to necessary precision (e.g., -04, +05:30)
  %Z   alphabetic time zone abbreviation (e.g., EDT)

By default, date pads numeric fields with zeroes.
The following optional flags may follow '%':

  -  (hyphen) do not pad the field
  _  (underscore) pad with spaces
  0  (zero) pad with zeros
  ^  use upper case if possible
  #  use opposite case if possible

After any flags comes an optional field width, as a decimal number;
then an optional modifier, which is either
E to use the locale's alternate representations if available, or
O to use the locale's alternate numeric symbols if available.

Examples:
Convert seconds since the epoch (1970-01-01 UTC) to a date
  $ date --date='@2147483647'

Show the time on the west coast of the US (use tzselect(1) to find TZ)
  $ TZ='America/Los_Angeles' date

Show the local time for 9AM next Friday on the west coast of the US
  $ date --date='TZ="America/Los_Angeles" 09:00 next Fri'

GNU coreutils online help: <http://www.gnu.org/software/coreutils/>
Full documentation at: <http://www.gnu.org/software/coreutils/date>
or available locally via: info '(coreutils) date invocation'

Thu Jul 19 19:47:08 UTC 2018

```
## uname -a
```

Linux oob-mgmt-server 4.1.0-cl-6-amd64 #1 SMP Cumulus 4.1.33-1+cl3u12 (2018-02-25) x86_64 GNU/Linux

```
```

Usage: uname [OPTION]...
Print certain system information.  With no OPTION, same as -s.

  -a, --all                print all information, in the following order,
                             except omit -p and -i if unknown:
  -s, --kernel-name        print the kernel name
  -n, --nodename           print the network node hostname
  -r, --kernel-release     print the kernel release
  -v, --kernel-version     print the kernel version
  -m, --machine            print the machine hardware name
  -p, --processor          print the processor type or "unknown"
  -i, --hardware-platform  print the hardware platform or "unknown"
  -o, --operating-system   print the operating system
      --help     display this help and exit
      --version  output version information and exit

GNU coreutils online help: <http://www.gnu.org/software/coreutils/>
Full documentation at: <http://www.gnu.org/software/coreutils/uname>
or available locally via: info '(coreutils) uname invocation'

Linux oob-mgmt-server 4.1.0-cl-6-amd64 #1 SMP Cumulus 4.1.33-1+cl3u12 (2018-02-25) x86_64 GNU/Linux

```
## net show version
```

NCLU_VERSION=1.0
DISTRIB_ID="Cumulus Linux"
DISTRIB_RELEASE=3.5.3
DISTRIB_DESCRIPTION="Cumulus Linux 3.5.3"

```
```

The following commands contain keyword(s) 'show', 'version'

    net show version


```
## net show system
```

Cumulus VX
Cumulus Linux 3.5.3
Build: Cumulus Linux 3.5.3
Uptime: 1:40:18.690000

```
```

The following commands contain keyword(s) 'show', 'system'

    net show system


```
