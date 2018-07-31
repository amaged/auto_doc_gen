# System Resources
## sudo cl-resource-query
```

route table mode is not available

```
```

usage: cl-resource-query [-h] [-k | -j]

Cumulus Resource Reporting

optional arguments:
  -h, --help       show this help message and exit
  -k, --key-value  Report key=value pairs
  -j, --json       Display JSON output

```
## top
```

'unknown': unknown terminal type.

```
```

top: inappropriate '-help'
Usage:
  top -hv | -bcHiOSs -d secs -n max -u|U user -p pid(s) -o field -w [cols]

'unknown': unknown terminal type.

```
## ps -elf
```

F S UID        PID  PPID  C PRI  NI ADDR SZ WCHAN  STIME TTY          TIME CMD
4 S root         1     0  0  80   0 -  7348 ep_pol 18:06 ?        00:00:32 /sbin/init
1 S root         2     0  0  80   0 -     0 kthrea 18:06 ?        00:00:00 [kthreadd]
1 S root         3     2  0  80   0 -     0 smpboo 18:06 ?        00:00:40 [ksoftirqd/0]
1 S root         5     2  0  60 -20 -     0 worker 18:06 ?        00:00:00 [kworker/0:0H]
1 S root         7     2  0  80   0 -     0 rcu_gp 18:06 ?        00:00:05 [rcu_sched]
1 S root         8     2  0  80   0 -     0 rcu_gp 18:06 ?        00:00:00 [rcu_bh]
1 S root         9     2  0 -40   - -     0 smpboo 18:06 ?        00:00:01 [migration/0]
5 S root        10     2  0 -40   - -     0 smpboo 18:06 ?        00:00:00 [watchdog/0]
5 S root        11     2  0 -40   - -     0 smpboo 18:06 ?        00:00:00 [watchdog/1]
1 S root        12     2  0 -40   - -     0 smpboo 18:06 ?        00:00:01 [migration/1]
1 S root        13     2  0  80   0 -     0 smpboo 18:06 ?        00:00:40 [ksoftirqd/1]
1 S root        15     2  0  60 -20 -     0 worker 18:06 ?        00:00:00 [kworker/1:0H]
1 S root        16     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [khelper]
5 S root        17     2  0  80   0 -     0 devtmp 18:06 ?        00:00:00 [kdevtmpfs]
1 S root        18     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [netns]
1 S root        19     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [perf]
1 S root        20     2  0  80   0 -     0 watchd 18:06 ?        00:00:00 [khungtaskd]
1 S root        21     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [writeback]
1 S root        23     2  0  85   5 -     0 ksm_sc 18:06 ?        00:00:00 [ksmd]
1 S root        24     2  0  99  19 -     0 khugep 18:06 ?        00:00:00 [khugepaged]
1 S root        25     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [crypto]
1 S root        26     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [kintegrityd]
1 S root        27     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [bioset]
1 S root        28     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [kblockd]
1 S root        29     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [ata_sff]
1 S root        30     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [edac-poller]
1 S root        32     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [rpciod]
1 S root        33     2  0  80   0 -     0 kswapd 18:06 ?        00:00:00 [kswapd0]
1 S root        34     2  0  80   0 -     0 fsnoti 18:06 ?        00:00:00 [fsnotify_mark]
1 S root        35     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [nfsiod]
1 S root        44     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [kthrotld]
1 S root        45     2  0  80   0 -     0 scsi_e 18:06 ?        00:00:00 [scsi_eh_0]
1 S root        46     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [scsi_tmf_0]
1 S root        47     2  0  80   0 -     0 scsi_e 18:06 ?        00:00:00 [scsi_eh_1]
1 S root        48     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [scsi_tmf_1]
1 S root        51     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [ipv6_addrconf]
1 S root        52     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [deferwq]
1 S root        89     2  0  60 -20 -     0 worker 18:06 ?        00:00:01 [kworker/1:1H]
1 S root        91     2  0  60 -20 -     0 worker 18:06 ?        00:00:01 [kworker/0:1H]
1 S root       103     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [bioset]
1 S root       120     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-worker]
1 S root       122     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-worker-hi]
1 S root       123     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-delalloc]
1 S root       124     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-flush_del]
1 S root       125     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-cache]
1 S root       126     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-submit]
1 S root       127     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-fixup]
1 S root       128     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio]
1 S root       129     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio-met]
1 S root       130     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio-met]
1 S root       131     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio-rai]
1 S root       132     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio-rep]
1 S root       133     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-rmw]
1 S root       134     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio-wri]
1 S root       135     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-freespace]
1 S root       136     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-delayed-m]
1 S root       137     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-readahead]
1 S root       138     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-qgroup-re]
1 S root       139     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-extent-re]
1 S root       140     2  0  80   0 -     0 cleane 18:06 ?        00:00:00 [btrfs-cleaner]
1 S root       141     2  0  80   0 -     0 transa 18:06 ?        00:00:06 [btrfs-transacti]
1 S root       254     2  0  80   0 -     0 kaudit 18:07 ?        00:00:00 [kauditd]
4 S root       256     1  0  80   0 -  8241 ep_pol 18:07 ?        00:00:05 /lib/systemd/systemd-journald
4 S root       258     1  0  80   0 -  9873 ep_pol 18:07 ?        00:00:00 /lib/systemd/systemd-udevd
4 S root       363     1  0  76  -4 - 12080 ep_pol 18:07 ?        00:00:04 /sbin/auditd -n
4 S root       394     1  0  85   5 -  6876 hrtime 18:07 ?        00:00:00 /usr/sbin/cron -f -L 38
4 S ctsauth    397     1  0  80   0 - 12448 poll_s 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/cts-auth
4 S root       398     1  0  80   0 - 79132 ep_pol 18:07 ?        00:00:03 /usr/bin/python /usr/local/bin/gateone
4 S message+   402     1  0  80   0 - 10557 ep_pol 18:07 ?        00:00:01 /usr/bin/dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd-activation
1 S root       435     2  0  60 -20 -     0 worker 19:39 ?        00:00:00 [kworker/u5:1]
0 S root       437     1  0  80   0 -  1064 poll_s 18:07 ?        00:00:00 /usr/sbin/acpid
4 S root       438     1  0  80   0 -  4964 ep_pol 18:07 ?        00:00:00 /lib/systemd/systemd-logind
4 S root       441     1  0  80   0 - 65182 poll_s 18:07 ?        00:00:01 /usr/sbin/rsyslogd -n
4 S root       464     1  0  80   0 -  3604 wait_w 18:07 tty1     00:00:00 /sbin/agetty --noclear tty1 linux
5 S root       489     1  0  80   0 -  1057 hrtime 18:07 ?        00:00:00 /usr/sbin/wd_keepalive 
4 S root       506     1  0  80   0 -  3181 poll_s 18:07 ?        00:00:00 /usr/sbin/mcelog --ignorenodev --daemon --foreground
4 S root       507     1  0  80   0 -  9175 poll_s 18:07 ?        00:00:21 /usr/bin/python /usr/sbin/smond
1 S root       508     1  0  80   0 - 36705 sigsus 18:07 ?        00:00:00 nginx: master process /usr/sbin/nginx -g daemon on; master_process on;
5 S www-data   509   508  0  80   0 - 36705 ep_pol 18:07 ?        00:00:00 nginx: worker process                           
4 S root       510     1  0  80   0 -  9157 poll_s 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/ledmgrd
5 S www-data   511   508  0  80   0 - 36705 ep_pol 18:07 ?        00:00:01 nginx: worker process                           
5 S www-data   512   508  0  80   0 - 36705 ep_pol 18:07 ?        00:00:01 nginx: worker process                           
5 S www-data   513   508  0  80   0 - 36705 ep_pol 18:07 ?        00:00:01 nginx: worker process                           
4 S root       514     1  0  80   0 -  9170 poll_s 18:07 ?        00:00:02 /usr/bin/python /usr/sbin/pwmd
5 S root       515     1  0  80   0 -  4819 hrtime 18:07 ?        00:00:00 /usr/sbin/irqbalance --pid=/var/run/irqbalance.pid
4 S root       554     1  0  75  -5 - 16573 poll_s 18:07 ?        00:00:00 /usr/sbin/switchd -vx
4 S root       575     1  0  80   0 - 14143 poll_s 18:07 ?        00:00:00 /usr/bin/python /usr/sbin/portwd
4 S uuidd      703     1  0  80   0 -  6447 skb_re 18:07 ?        00:00:00 /usr/sbin/uuidd --socket-activation
4 S root       755     1  1  80   0 - 105202 poll_s 18:07 ?       00:01:03 /usr/bin/python /usr/bin/neighmgrd
4 S root       757     1  2  80   0 - 46532 skb_re 18:07 ?        00:02:15 /usr/bin/python -O /usr/sbin/netd -d
4 S root       758     1  0  80   0 -  5465 wait   18:07 ?        00:00:00 /bin/bash /usr/lib/cumulus/sysmonitor
4 S root       759     1  0  80   0 - 90297 poll_s 18:07 ?        00:00:15 /usr/bin/python /usr/sbin/netqd --daemon
5 S frr        791     1  0  75  -5 - 20048 poll_s 18:07 ?        00:00:08 /usr/lib/frr/zebra -M snmp -s 90000000 --daemon -A 127.0.0.1
5 S frr        798     1  0  75  -5 - 57777 poll_s 18:07 ?        00:00:15 /usr/lib/frr/bgpd -M snmp --daemon -A 127.0.0.1
5 S root       806     1  0  75  -5 - 11789 poll_s 18:07 ?        00:00:06 /usr/lib/frr/watchfrr -d -r /usr/sbin/servicebBfrrbBrestartbB%s -s /usr/sbin/servicebBfrrbBstartbB%s -k /usr/sbin/servicebBfrrbBstopbB%s -b bB -t 90 zebra bgpd
4 S root       834     1  0  80   0 - 14025 unix_s 18:07 ?        00:00:00 lldpd: monitor.        
4 S ntp        835     1  0  80   0 -  8358 poll_s 18:07 ?        00:00:01 /usr/sbin/ntpd -n -u ntp:ntp -g
4 S root       836     1  0  80   0 -  4331 poll_s 18:07 ?        00:00:00 /usr/sbin/ptmd -l INFO
4 S root       837     1  1  80   0 - 162040 futex_ 18:07 ?       00:01:03 /usr/bin/dockerd -H tcp://0.0.0.0:2375 -H unix:///var/run/docker.sock
4 S root       838     1  0  80   0 - 24635 poll_s 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/netq-notifier
4 S root       839     1  0  80   0 -  7679 poll_s 18:07 ?        00:00:00 /usr/sbin/dhcpd --nl -f -q
4 S root       840     1  1  80   0 - 20706 ep_pol 18:07 ?        00:01:36 /usr/bin/python /usr/sbin/netq-agent
4 S root       841     1  0  80   0 -  3559 wait_w 18:07 ttyS0    00:00:00 /sbin/agetty --keep-baud 115200 38400 9600 ttyS0 vt102
5 S _lldpd     857   834  0  80   0 - 14025 ep_pol 18:07 ?        00:00:01 lldpd: 2 neighbors.    
4 S root       887     1  0  80   0 - 13796 poll_s 18:07 ?        00:00:00 /usr/sbin/sshd -D
4 S root       899   837  0  80   0 - 77556 ep_pol 18:07 ?        00:00:42 docker-containerd --config /var/run/docker/containerd/containerd.toml
4 S root      1128   899  0  80   0 -  1878 ep_pol 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/4cc26bfbf1be6a4599c15f9b835a9f62a605488e0eb79e5b5ac857adbc200a80 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
4 S root      1130   899  0  80   0 -  1878 futex_ 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/11b15c8fbacfa7624f9451cda0ac73e68f8beca6d145381655bcc2b94ad46693 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
4 S root      1136   899  0  80   0 -  1878 ep_pol 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/b2f5e1e9d1a2f5838473ec5f2396182ff65a4b74ba660b033f65e90b2c583c6a -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
4 S root      1146   899  0  80   0 -  1878 futex_ 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/b6722ff84f52a4ea19d367de60a29506cf4f756eb9b40516b68c21a18e02b7fb -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
4 S root      1152   899  0  80   0 -  1878 futex_ 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/d1342dce41740c07fd9ae88ce9a952edcf3cec36a3dd5c9546dad8c0e09f8141 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
1 S root      1191     2  0  80   0 -     0 worker 19:42 ?        00:00:00 [kworker/1:2]
4 S root      1215  1136  0  80   0 -  4126 ep_pol 18:08 ?        00:00:58 redis-sentinel /etc/cts/redis/snt1.conf
4 S root      1216  1130  0  80   0 -  2798 ep_pol 18:08 ?        00:00:00 /portainer
4 S root      1217  1152  0  80   0 - 14834 futex_ 18:08 ?        00:00:40 influxd
4 S root      1218  1128  0  80   0 -  1056 sigtim 18:08 ?        00:00:00 /tini -g -- /usr/sbin/netqd --daemon
4 S systemd+  1228  1146  1  80   0 -  5777 ep_pol 18:08 ?        00:01:22 redis-server /etc/cts/redis/redis_6379.conf
4 S root      1321  1218  0  80   0 - 85726 poll_s 18:08 ?        00:00:20 /usr/bin/python /usr/sbin/netqd --daemon
4 S root      1333     1  1  80   0 - 54960 poll_s 18:08 ?        00:01:16 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-gui-compose.yml up --no-color
4 S admin     1334     1  1  80   0 - 52854 poll_s 18:08 ?        00:01:17 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-influxdb-compose.yml up --no-color
4 S root      1359     1  1  80   0 - 91846 poll_s 18:08 ?        00:01:14 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-base-compose.yml up --no-color
4 S root      1911   887  0  80   0 - 21718 poll_s 19:46 ?        00:00:00 sshd: cumulus [priv]
1 S root      1923     2  0  80   0 -     0 worker 19:46 ?        00:00:00 [kworker/u4:0]
0 S root      1959   758  0  80   0 -  1452 hrtime 19:46 ?        00:00:00 sleep 60
5 S cumulus   2040  1911  0  80   0 - 21718 poll_s 19:47 ?        00:00:00 sshd: cumulus@notty 
0 S cumulus   2041  2040  0  80   0 -  3307 wait   19:47 ?        00:00:00 bash -c sh run.commands &> output
0 S cumulus   2042  2041  0  80   0 -  1084 wait   19:47 ?        00:00:00 sh run.commands
4 S root      2299  2042  0  80   0 - 11708 poll_s 19:47 ?        00:00:00 sudo nohup ps -elf
4 R root      2304  2299  0  80   0 -  4775 -      19:47 ?        00:00:00 ps -elf
1 S root     17616     2  0  80   0 -     0 worker 18:45 ?        00:00:01 [kworker/u4:1]
0 S root     25029   398  0  80   0 -  1084 wait   19:09 pts/1    00:00:00 /bin/sh -c dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S '/tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET%' --sshfp -a '-oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"'; sleep .1
0 S root     25030 25029  0  80   0 -  1537 poll_s 19:09 pts/1    00:00:00 dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET% --sshfp -a -oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"
1 S root     25031 25030  0  80   0 -  3673 poll_s 19:09 ?        00:00:00 dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET% --sshfp -a -oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"
0 S root     25032 25031  0  80   0 -  1084 wait   19:09 pts/2    00:00:00 sh -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22 && rm -f /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22
0 S root     25034 25032  0  80   0 -  1084 wait   19:09 pts/2    00:00:00 /bin/sh /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22
4 S root     25035 25034  0  80   0 - 11108 poll_s 19:09 pts/2    00:00:00 ssh -M -S/tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/JTw8Am_C -x -F/opt/gateone/users/ANONYMOUS/.ssh/config -oNoHostAuthenticationForLocalhost=yes -oVerifyHostKeyDNS=yes -oPreferredAuthentications=keyboard-interactive,password -oIdentitiesOnly=yes -oSendEnv=GO_TERM GO_LOCATION GO_SESSION -p 22 -l cumulus -oUserKnownHostsFile="/opt/gateone/users/ANONYMOUS/.ssh/known_hosts" localhost
4 S root     25036   887  0  80   0 - 21162 poll_s 19:09 ?        00:00:00 sshd: cumulus [priv]
5 S cumulus  25079 25036  0  80   0 - 21162 poll_s 19:09 ?        00:00:00 sshd: cumulus@pts/3 
0 S cumulus  25080 25079  0  80   0 -  6264 wait_w 19:09 pts/3    00:00:00 -bash
1 S root     26130     2  0  80   0 -     0 worker 19:13 ?        00:00:00 [kworker/u4:2]
1 S root     27520     2  0  80   0 -     0 worker 19:17 ?        00:00:00 [kworker/1:1]
1 S root     28137     2  0  80   0 -     0 worker 19:19 ?        00:00:00 [kworker/u4:3]
1 S root     28598     2  0  60 -20 -     0 worker 19:21 ?        00:00:00 [kworker/u5:2]
1 S root     30600     2  0  80   0 -     0 worker 19:27 ?        00:00:00 [kworker/1:0]
1 S root     31693     2  0  80   0 -     0 worker 19:32 ?        00:00:00 [kworker/0:0]
1 S root     31742     2  0  60 -20 -     0 worker 19:33 ?        00:00:00 [kworker/u5:0]
1 S root     32620     2  0  80   0 -     0 worker 19:37 ?        00:00:00 [kworker/0:1]

```
```


Usage:
 ps [options]

 Try 'ps --help <simple|list|output|threads|misc|all>'
  or 'ps --help <s|l|o|t|m|a>'
 for additional help text.

For more details see ps(1).

F S UID        PID  PPID  C PRI  NI ADDR SZ WCHAN  STIME TTY          TIME CMD
4 S root         1     0  0  80   0 -  7348 ep_pol 18:06 ?        00:00:32 /sbin/init
1 S root         2     0  0  80   0 -     0 kthrea 18:06 ?        00:00:00 [kthreadd]
1 S root         3     2  0  80   0 -     0 smpboo 18:06 ?        00:00:40 [ksoftirqd/0]
1 S root         5     2  0  60 -20 -     0 worker 18:06 ?        00:00:00 [kworker/0:0H]
1 S root         7     2  0  80   0 -     0 rcu_gp 18:06 ?        00:00:05 [rcu_sched]
1 S root         8     2  0  80   0 -     0 rcu_gp 18:06 ?        00:00:00 [rcu_bh]
1 S root         9     2  0 -40   - -     0 smpboo 18:06 ?        00:00:01 [migration/0]
5 S root        10     2  0 -40   - -     0 smpboo 18:06 ?        00:00:00 [watchdog/0]
5 S root        11     2  0 -40   - -     0 smpboo 18:06 ?        00:00:00 [watchdog/1]
1 S root        12     2  0 -40   - -     0 smpboo 18:06 ?        00:00:01 [migration/1]
1 S root        13     2  0  80   0 -     0 smpboo 18:06 ?        00:00:40 [ksoftirqd/1]
1 S root        15     2  0  60 -20 -     0 worker 18:06 ?        00:00:00 [kworker/1:0H]
1 S root        16     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [khelper]
5 S root        17     2  0  80   0 -     0 devtmp 18:06 ?        00:00:00 [kdevtmpfs]
1 S root        18     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [netns]
1 S root        19     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [perf]
1 S root        20     2  0  80   0 -     0 watchd 18:06 ?        00:00:00 [khungtaskd]
1 S root        21     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [writeback]
1 S root        23     2  0  85   5 -     0 ksm_sc 18:06 ?        00:00:00 [ksmd]
1 S root        24     2  0  99  19 -     0 khugep 18:06 ?        00:00:00 [khugepaged]
1 S root        25     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [crypto]
1 S root        26     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [kintegrityd]
1 S root        27     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [bioset]
1 S root        28     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [kblockd]
1 S root        29     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [ata_sff]
1 S root        30     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [edac-poller]
1 S root        32     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [rpciod]
1 S root        33     2  0  80   0 -     0 kswapd 18:06 ?        00:00:00 [kswapd0]
1 S root        34     2  0  80   0 -     0 fsnoti 18:06 ?        00:00:00 [fsnotify_mark]
1 S root        35     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [nfsiod]
1 S root        44     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [kthrotld]
1 S root        45     2  0  80   0 -     0 scsi_e 18:06 ?        00:00:00 [scsi_eh_0]
1 S root        46     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [scsi_tmf_0]
1 S root        47     2  0  80   0 -     0 scsi_e 18:06 ?        00:00:00 [scsi_eh_1]
1 S root        48     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [scsi_tmf_1]
1 S root        51     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [ipv6_addrconf]
1 S root        52     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [deferwq]
1 S root        89     2  0  60 -20 -     0 worker 18:06 ?        00:00:01 [kworker/1:1H]
1 S root        91     2  0  60 -20 -     0 worker 18:06 ?        00:00:01 [kworker/0:1H]
1 S root       103     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [bioset]
1 S root       120     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-worker]
1 S root       122     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-worker-hi]
1 S root       123     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-delalloc]
1 S root       124     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-flush_del]
1 S root       125     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-cache]
1 S root       126     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-submit]
1 S root       127     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-fixup]
1 S root       128     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio]
1 S root       129     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio-met]
1 S root       130     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio-met]
1 S root       131     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio-rai]
1 S root       132     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio-rep]
1 S root       133     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-rmw]
1 S root       134     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-endio-wri]
1 S root       135     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-freespace]
1 S root       136     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-delayed-m]
1 S root       137     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-readahead]
1 S root       138     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-qgroup-re]
1 S root       139     2  0  60 -20 -     0 rescue 18:06 ?        00:00:00 [btrfs-extent-re]
1 S root       140     2  0  80   0 -     0 cleane 18:06 ?        00:00:00 [btrfs-cleaner]
1 S root       141     2  0  80   0 -     0 transa 18:06 ?        00:00:06 [btrfs-transacti]
1 S root       254     2  0  80   0 -     0 kaudit 18:07 ?        00:00:00 [kauditd]
4 S root       256     1  0  80   0 -  8241 ep_pol 18:07 ?        00:00:05 /lib/systemd/systemd-journald
4 S root       258     1  0  80   0 -  9873 ep_pol 18:07 ?        00:00:00 /lib/systemd/systemd-udevd
4 S root       363     1  0  76  -4 - 12080 ep_pol 18:07 ?        00:00:04 /sbin/auditd -n
4 S root       394     1  0  85   5 -  6876 hrtime 18:07 ?        00:00:00 /usr/sbin/cron -f -L 38
4 S ctsauth    397     1  0  80   0 - 12448 poll_s 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/cts-auth
4 S root       398     1  0  80   0 - 79132 ep_pol 18:07 ?        00:00:03 /usr/bin/python /usr/local/bin/gateone
4 S message+   402     1  0  80   0 - 10557 ep_pol 18:07 ?        00:00:01 /usr/bin/dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd-activation
1 S root       435     2  0  60 -20 -     0 worker 19:39 ?        00:00:00 [kworker/u5:1]
0 S root       437     1  0  80   0 -  1064 poll_s 18:07 ?        00:00:00 /usr/sbin/acpid
4 S root       438     1  0  80   0 -  4964 ep_pol 18:07 ?        00:00:00 /lib/systemd/systemd-logind
4 S root       441     1  0  80   0 - 65182 poll_s 18:07 ?        00:00:01 /usr/sbin/rsyslogd -n
4 S root       464     1  0  80   0 -  3604 wait_w 18:07 tty1     00:00:00 /sbin/agetty --noclear tty1 linux
5 S root       489     1  0  80   0 -  1057 hrtime 18:07 ?        00:00:00 /usr/sbin/wd_keepalive 
4 S root       506     1  0  80   0 -  3181 poll_s 18:07 ?        00:00:00 /usr/sbin/mcelog --ignorenodev --daemon --foreground
4 S root       507     1  0  80   0 -  9175 poll_s 18:07 ?        00:00:21 /usr/bin/python /usr/sbin/smond
1 S root       508     1  0  80   0 - 36705 sigsus 18:07 ?        00:00:00 nginx: master process /usr/sbin/nginx -g daemon on; master_process on;
5 S www-data   509   508  0  80   0 - 36705 ep_pol 18:07 ?        00:00:00 nginx: worker process                           
4 S root       510     1  0  80   0 -  9157 poll_s 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/ledmgrd
5 S www-data   511   508  0  80   0 - 36705 ep_pol 18:07 ?        00:00:01 nginx: worker process                           
5 S www-data   512   508  0  80   0 - 36705 ep_pol 18:07 ?        00:00:01 nginx: worker process                           
5 S www-data   513   508  0  80   0 - 36705 ep_pol 18:07 ?        00:00:01 nginx: worker process                           
4 S root       514     1  0  80   0 -  9170 poll_s 18:07 ?        00:00:02 /usr/bin/python /usr/sbin/pwmd
5 S root       515     1  0  80   0 -  4819 hrtime 18:07 ?        00:00:00 /usr/sbin/irqbalance --pid=/var/run/irqbalance.pid
4 S root       554     1  0  75  -5 - 16573 poll_s 18:07 ?        00:00:00 /usr/sbin/switchd -vx
4 S root       575     1  0  80   0 - 14143 poll_s 18:07 ?        00:00:00 /usr/bin/python /usr/sbin/portwd
4 S uuidd      703     1  0  80   0 -  6447 skb_re 18:07 ?        00:00:00 /usr/sbin/uuidd --socket-activation
4 S root       755     1  1  80   0 - 105202 poll_s 18:07 ?       00:01:03 /usr/bin/python /usr/bin/neighmgrd
4 S root       757     1  2  80   0 - 46532 skb_re 18:07 ?        00:02:15 /usr/bin/python -O /usr/sbin/netd -d
4 S root       758     1  0  80   0 -  5465 wait   18:07 ?        00:00:00 /bin/bash /usr/lib/cumulus/sysmonitor
4 S root       759     1  0  80   0 - 90297 poll_s 18:07 ?        00:00:15 /usr/bin/python /usr/sbin/netqd --daemon
5 S frr        791     1  0  75  -5 - 20048 poll_s 18:07 ?        00:00:08 /usr/lib/frr/zebra -M snmp -s 90000000 --daemon -A 127.0.0.1
5 S frr        798     1  0  75  -5 - 57777 poll_s 18:07 ?        00:00:15 /usr/lib/frr/bgpd -M snmp --daemon -A 127.0.0.1
5 S root       806     1  0  75  -5 - 11789 poll_s 18:07 ?        00:00:06 /usr/lib/frr/watchfrr -d -r /usr/sbin/servicebBfrrbBrestartbB%s -s /usr/sbin/servicebBfrrbBstartbB%s -k /usr/sbin/servicebBfrrbBstopbB%s -b bB -t 90 zebra bgpd
4 S root       834     1  0  80   0 - 14025 unix_s 18:07 ?        00:00:00 lldpd: monitor.        
4 S ntp        835     1  0  80   0 -  8358 poll_s 18:07 ?        00:00:01 /usr/sbin/ntpd -n -u ntp:ntp -g
4 S root       836     1  0  80   0 -  4331 poll_s 18:07 ?        00:00:00 /usr/sbin/ptmd -l INFO
4 S root       837     1  1  80   0 - 162040 futex_ 18:07 ?       00:01:03 /usr/bin/dockerd -H tcp://0.0.0.0:2375 -H unix:///var/run/docker.sock
4 S root       838     1  0  80   0 - 24635 poll_s 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/netq-notifier
4 S root       839     1  0  80   0 -  7679 poll_s 18:07 ?        00:00:00 /usr/sbin/dhcpd --nl -f -q
4 S root       840     1  1  80   0 - 20706 ep_pol 18:07 ?        00:01:36 /usr/bin/python /usr/sbin/netq-agent
4 S root       841     1  0  80   0 -  3559 wait_w 18:07 ttyS0    00:00:00 /sbin/agetty --keep-baud 115200 38400 9600 ttyS0 vt102
5 S _lldpd     857   834  0  80   0 - 14025 ep_pol 18:07 ?        00:00:01 lldpd: 2 neighbors.    
4 S root       887     1  0  80   0 - 13796 poll_s 18:07 ?        00:00:00 /usr/sbin/sshd -D
4 S root       899   837  0  80   0 - 77556 ep_pol 18:07 ?        00:00:42 docker-containerd --config /var/run/docker/containerd/containerd.toml
4 S root      1128   899  0  80   0 -  1878 ep_pol 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/4cc26bfbf1be6a4599c15f9b835a9f62a605488e0eb79e5b5ac857adbc200a80 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
4 S root      1130   899  0  80   0 -  1878 futex_ 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/11b15c8fbacfa7624f9451cda0ac73e68f8beca6d145381655bcc2b94ad46693 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
4 S root      1136   899  0  80   0 -  1878 ep_pol 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/b2f5e1e9d1a2f5838473ec5f2396182ff65a4b74ba660b033f65e90b2c583c6a -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
4 S root      1146   899  0  80   0 -  1878 futex_ 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/b6722ff84f52a4ea19d367de60a29506cf4f756eb9b40516b68c21a18e02b7fb -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
4 S root      1152   899  0  80   0 -  1878 futex_ 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/d1342dce41740c07fd9ae88ce9a952edcf3cec36a3dd5c9546dad8c0e09f8141 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
1 S root      1191     2  0  80   0 -     0 worker 19:42 ?        00:00:00 [kworker/1:2]
4 S root      1215  1136  0  80   0 -  4126 ep_pol 18:08 ?        00:00:58 redis-sentinel /etc/cts/redis/snt1.conf
4 S root      1216  1130  0  80   0 -  2798 ep_pol 18:08 ?        00:00:00 /portainer
4 S root      1217  1152  0  80   0 - 14834 futex_ 18:08 ?        00:00:40 influxd
4 S root      1218  1128  0  80   0 -  1056 sigtim 18:08 ?        00:00:00 /tini -g -- /usr/sbin/netqd --daemon
4 S systemd+  1228  1146  1  80   0 -  5777 ep_pol 18:08 ?        00:01:22 redis-server /etc/cts/redis/redis_6379.conf
4 S root      1321  1218  0  80   0 - 85726 poll_s 18:08 ?        00:00:20 /usr/bin/python /usr/sbin/netqd --daemon
4 S root      1333     1  1  80   0 - 54960 poll_s 18:08 ?        00:01:16 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-gui-compose.yml up --no-color
4 S admin     1334     1  1  80   0 - 52854 poll_s 18:08 ?        00:01:17 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-influxdb-compose.yml up --no-color
4 S root      1359     1  1  80   0 - 91846 poll_s 18:08 ?        00:01:14 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-base-compose.yml up --no-color
4 S root      1911   887  0  80   0 - 21718 poll_s 19:46 ?        00:00:00 sshd: cumulus [priv]
1 S root      1923     2  0  80   0 -     0 worker 19:46 ?        00:00:00 [kworker/u4:0]
0 S root      1959   758  0  80   0 -  1452 hrtime 19:46 ?        00:00:00 sleep 60
5 S cumulus   2040  1911  0  80   0 - 21718 poll_s 19:47 ?        00:00:00 sshd: cumulus@notty 
0 S cumulus   2041  2040  0  80   0 -  3307 wait   19:47 ?        00:00:00 bash -c sh run.commands &> output
0 S cumulus   2042  2041  0  80   0 -  1084 wait   19:47 ?        00:00:00 sh run.commands
4 S root      2299  2042  0  80   0 - 11708 poll_s 19:47 ?        00:00:00 sudo nohup ps -elf
4 R root      2304  2299  0  80   0 -  4775 -      19:47 ?        00:00:00 ps -elf
1 S root     17616     2  0  80   0 -     0 worker 18:45 ?        00:00:01 [kworker/u4:1]
0 S root     25029   398  0  80   0 -  1084 wait   19:09 pts/1    00:00:00 /bin/sh -c dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S '/tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET%' --sshfp -a '-oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"'; sleep .1
0 S root     25030 25029  0  80   0 -  1537 poll_s 19:09 pts/1    00:00:00 dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET% --sshfp -a -oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"
1 S root     25031 25030  0  80   0 -  3673 poll_s 19:09 ?        00:00:00 dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET% --sshfp -a -oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"
0 S root     25032 25031  0  80   0 -  1084 wait   19:09 pts/2    00:00:00 sh -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22 && rm -f /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22
0 S root     25034 25032  0  80   0 -  1084 wait   19:09 pts/2    00:00:00 /bin/sh /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22
4 S root     25035 25034  0  80   0 - 11108 poll_s 19:09 pts/2    00:00:00 ssh -M -S/tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/JTw8Am_C -x -F/opt/gateone/users/ANONYMOUS/.ssh/config -oNoHostAuthenticationForLocalhost=yes -oVerifyHostKeyDNS=yes -oPreferredAuthentications=keyboard-interactive,password -oIdentitiesOnly=yes -oSendEnv=GO_TERM GO_LOCATION GO_SESSION -p 22 -l cumulus -oUserKnownHostsFile="/opt/gateone/users/ANONYMOUS/.ssh/known_hosts" localhost
4 S root     25036   887  0  80   0 - 21162 poll_s 19:09 ?        00:00:00 sshd: cumulus [priv]
5 S cumulus  25079 25036  0  80   0 - 21162 poll_s 19:09 ?        00:00:00 sshd: cumulus@pts/3 
0 S cumulus  25080 25079  0  80   0 -  6264 wait_w 19:09 pts/3    00:00:00 -bash
1 S root     26130     2  0  80   0 -     0 worker 19:13 ?        00:00:00 [kworker/u4:2]
1 S root     27520     2  0  80   0 -     0 worker 19:17 ?        00:00:00 [kworker/1:1]
1 S root     28137     2  0  80   0 -     0 worker 19:19 ?        00:00:00 [kworker/u4:3]
1 S root     28598     2  0  60 -20 -     0 worker 19:21 ?        00:00:00 [kworker/u5:2]
1 S root     30600     2  0  80   0 -     0 worker 19:27 ?        00:00:00 [kworker/1:0]
1 S root     31693     2  0  80   0 -     0 worker 19:32 ?        00:00:00 [kworker/0:0]
1 S root     31742     2  0  60 -20 -     0 worker 19:33 ?        00:00:00 [kworker/u5:0]
1 S root     32620     2  0  80   0 -     0 worker 19:37 ?        00:00:00 [kworker/0:1]

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
## sensors
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
temp1:        +25.0°C  (low  =  +5.0°C, high = +80.0°C)
                       (crit low =  +0.0°C, crit = +85.0°C)
temp2:        +25.0°C  (low  =  +5.0°C, high = +80.0°C)
                       (crit low =  +0.0°C, crit = +85.0°C)
temp3:        +25.0°C  (low  =  +5.0°C, high = +80.0°C)
                       (crit low =  +0.0°C, crit = +85.0°C)
temp4:        +25.0°C  (low  =  +5.0°C, high = +80.0°C)
                       (crit low =  +0.0°C, crit = +85.0°C)
temp5:        +25.0°C  (low  =  +5.0°C, high = +80.0°C)
                       (crit low =  +0.0°C, crit = +85.0°C)
temp6:        +25.0°C  (low  =  +5.0°C, high = +80.0°C)
                       (crit low =  +0.0°C, crit = +85.0°C)
temp7:        +25.0°C  (low  =  +5.0°C, high = +80.0°C)
                       (crit low =  +0.0°C, crit = +85.0°C)


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
## sudo smonctl
```

Fan1      (Fan Tray 1, Fan 1                     ):  OK
Fan2      (Fan Tray 1, Fan 2                     ):  OK
Fan3      (Fan Tray 2, Fan 1                     ):  OK
Fan4      (Fan Tray 2, Fan 2                     ):  OK
Fan5      (Fan Tray 3, Fan 1                     ):  OK
Fan6      (Fan Tray 3, Fan 2                     ):  OK
PSU1                                              :  OK
PSU2                                              :  OK
PSU1Fan1  (PSU1 Fan                              ):  OK
PSU1Temp1 (PSU1 Temp Sensor                      ):  OK
PSU2Fan1  (PSU2 Fan                              ):  OK
PSU2Temp1 (PSU2 Temp Sensor                      ):  OK
Temp1     (Board Sensor near CPU                 ):  OK
Temp2     (Board Sensor Near Virtual Switch      ):  OK
Temp3     (Board Sensor at Front Left Corner     ):  OK
Temp4     (Board Sensor at Front Right Corner    ):  OK
Temp5     (Board Sensor near Fan                 ):  OK

```
```

usage: smonctl [-h] [-j] [-s SENSOR] [-v]

Displays hardware sensors data

optional arguments:
  -h, --help            show this help message and exit
  -j, --json            Generate JSON output
  -s SENSOR, --sensor SENSOR
                        Display data for the given sensor
  -v, --verbose         Display detailed hardware sensors data

```
## sudo systemctl status wd_keepalive.service
```

● wd_keepalive.service - watchdog keepalive daemon
   Loaded: loaded (/lib/systemd/system/wd_keepalive.service; enabled)
   Active: active (running) since Thu 2018-07-19 18:07:31 UTC; 1h 39min ago
  Process: 451 ExecStart=/usr/sbin/wd_keepalive ${watchdog_options} (code=exited, status=0/SUCCESS)
  Process: 447 ExecStartPre=/bin/systemctl reset-failed watchdog.service (code=exited, status=0/SUCCESS)
  Process: 442 ExecStartPre=/bin/sh -c [ -z "${watchdog_module}" ] || [ "${watchdog_module}" = "none" ] || /sbin/modprobe ${watchdog_module} (code=exited, status=0/SUCCESS)
 Main PID: 489 (wd_keepalive)
   CGroup: /system.slice/wd_keepalive.service
           └─489 /usr/sbin/wd_keepalive 

Jul 19 18:07:31 oob-mgmt-server wd_keepalive[489]: starting watchdog keepalive daemon (5.14):
Jul 19 18:07:31 oob-mgmt-server wd_keepalive[489]: int=5 alive=/dev/watchdog realtime=no
Jul 19 18:07:31 oob-mgmt-server wd_keepalive[489]: watchdog now set to 30 seconds
Jul 19 18:07:31 oob-mgmt-server wd_keepalive[489]: hardware watchdog identity: Software Watchdog
Jul 19 18:07:31 oob-mgmt-server systemd[1]: Started watchdog keepalive daemon.

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
## ethtool -p --identify %DP TIME
```

ethtool: bad command line argument(s)
For more information run ethtool -h

```
```

nohup: failed to run command ‘ethtool’: No such file or directory

```
## netq show sensors
```

ERROR: Command not found

netq show sensors
                  ^ Invalid value here
Did you mean one of the following?
The following commands contain keyword(s) 'show', 'sensors'

    netq [<hostname>] show sensors all [json]
    netq [<hostname>] show sensors all around <text-time> [json]
    netq [<hostname>] show sensors all changes [json]
    netq [<hostname>] show sensors fan [<fan-name>] [json]
    netq [<hostname>] show sensors fan [<fan-name>] around <text-time> [json]
    netq [<hostname>] show sensors fan [<fan-name>] changes [json]
    netq [<hostname>] show sensors psu [<psu-name>] [json]
    netq [<hostname>] show sensors psu [<psu-name>] around <text-time> [json]
    netq [<hostname>] show sensors psu [<psu-name>] changes [json]
    netq [<hostname>] show sensors temp [<temp-name>] [json]
    netq [<hostname>] show sensors temp [<temp-name>] around <text-time> [json]
    netq [<hostname>] show sensors temp [<temp-name>] changes [json]


Unable to find command netq show sensors

```
```

The following commands contain keyword(s) 'show', 'sensors'

    netq [<hostname>] show sensors all [json]
    netq [<hostname>] show sensors all around <text-time> [json]
    netq [<hostname>] show sensors all changes [json]
    netq [<hostname>] show sensors fan [<fan-name>] [json]
    netq [<hostname>] show sensors fan [<fan-name>] around <text-time> [json]
    netq [<hostname>] show sensors fan [<fan-name>] changes [json]
    netq [<hostname>] show sensors psu [<psu-name>] [json]
    netq [<hostname>] show sensors psu [<psu-name>] around <text-time> [json]
    netq [<hostname>] show sensors psu [<psu-name>] changes [json]
    netq [<hostname>] show sensors temp [<temp-name>] [json]
    netq [<hostname>] show sensors temp [<temp-name>] around <text-time> [json]
    netq [<hostname>] show sensors temp [<temp-name>] changes [json]


Unable to find command netq show sensors --help

ERROR: Command not found

netq show sensors
                  ^ Invalid value here
Did you mean one of the following?
The following commands contain keyword(s) 'show', 'sensors'

    netq [<hostname>] show sensors all [json]
    netq [<hostname>] show sensors all around <text-time> [json]
    netq [<hostname>] show sensors all changes [json]
    netq [<hostname>] show sensors fan [<fan-name>] [json]
    netq [<hostname>] show sensors fan [<fan-name>] around <text-time> [json]
    netq [<hostname>] show sensors fan [<fan-name>] changes [json]
    netq [<hostname>] show sensors psu [<psu-name>] [json]
    netq [<hostname>] show sensors psu [<psu-name>] around <text-time> [json]
    netq [<hostname>] show sensors psu [<psu-name>] changes [json]
    netq [<hostname>] show sensors temp [<temp-name>] [json]
    netq [<hostname>] show sensors temp [<temp-name>] around <text-time> [json]
    netq [<hostname>] show sensors temp [<temp-name>] changes [json]


Unable to find command netq show sensors

```
## netq check sensors
```

[92mTotal Nodes: 11, Failed Nodes: 0, Checked Sensors: 119, Failed Sensors: 0[0m

```
```

The following commands contain keyword(s) 'check', 'sensors'

    netq check sensors [json]
    netq check sensors around <text-time> [json]


Unable to find command netq check sensors --help

[92mTotal Nodes: 11, Failed Nodes: 0, Checked Sensors: 119, Failed Sensors: 0[0m

```
## netq show interfaces
```


Matching link records:
Hostname          Interface                 Type     State      VRF              Details                             Last Changed
----------------- ------------------------- -------- ---------- ---------------- ----------------------------------- ----------------
leaf01            eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:46s
leaf01            lo                        loopback up         default          MTU:65536                           2d:19h:3m:46s
leaf01            mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:54s
                                                                                 Members: eth0
leaf01            swp1                      swp      up         default          LLDP: server01:eth1, MTU: 9000      2d:19h:3m:38s
leaf01            swp2                      swp      up         default          LLDP: server02:eth1, MTU: 9000      2d:19h:3m:38s
leaf01            swp44                     swp      up         default          LLDP: oob-mgmt-server:eth2,         2d:19h:3m:22s
                                                                                 MTU: 9000
leaf01            swp45                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp46                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp47                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp48                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp49                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp50                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp51                     swp      up         default          LLDP: spine01:swp1, MTU: 9000       2d:19h:3m:38s
leaf01            swp52                     swp      up         default          LLDP: spine02:swp1, MTU: 9000       2d:19h:3m:38s
leaf02            eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:46s
leaf02            lo                        loopback up         default          MTU:65536                           2d:19h:3m:46s
leaf02            mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:52s
                                                                                 Members: eth0
leaf02            swp1                      swp      up         default          LLDP: server01:eth2, MTU: 9000      2d:19h:3m:38s
leaf02            swp2                      swp      up         default          LLDP: server02:eth2, MTU: 9000      2d:19h:3m:38s
leaf02            swp44                     swp      up         default          LLDP: oob-mgmt-server:eth3,         2d:19h:3m:26s
                                                                                 MTU: 9000
leaf02            swp45                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp46                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp47                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp48                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp49                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp50                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp51                     swp      up         default          LLDP: spine01:swp2, MTU: 9000       2d:19h:3m:38s
leaf02            swp52                     swp      up         default          LLDP: spine02:swp2, MTU: 9000       2d:19h:3m:38s
leaf03            eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:46s
leaf03            lo                        loopback up         default          MTU:65536                           2d:19h:3m:46s
leaf03            mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:52s
                                                                                 Members: eth0
leaf03            swp1                      swp      up         default          LLDP: server03:eth1, MTU: 9000      2d:19h:3m:37s
leaf03            swp2                      swp      up         default          LLDP: server04:eth1, MTU: 9000      2d:19h:3m:37s
leaf03            swp45                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp46                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp47                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp48                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp49                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp50                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp51                     swp      up         default          LLDP: spine01:swp3, MTU: 9000       2d:19h:3m:38s
leaf03            swp52                     swp      up         default          LLDP: spine02:swp3, MTU: 9000       2d:19h:3m:37s
leaf04            eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:45s
leaf04            lo                        loopback up         default          MTU:65536                           2d:19h:3m:45s
leaf04            mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:54s
                                                                                 Members: eth0
leaf04            swp1                      swp      up         default          LLDP: server03:eth2, MTU: 9000      2d:19h:3m:38s
leaf04            swp2                      swp      up         default          LLDP: server04:eth2, MTU: 9000      2d:19h:3m:38s
leaf04            swp45                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp46                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp47                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp48                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp49                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp50                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp51                     swp      up         default          LLDP: spine01:swp4, MTU: 9000       2d:19h:3m:38s
leaf04            swp52                     swp      up         default          LLDP: spine02:swp4, MTU: 9000       2d:19h:3m:38s
oob-mgmt-server   docker0                   bridge   down       default          Members: , Root Bridge: No Info,    1h:37m:52s
                                                                                 Root port No Info, MTU: 1500
oob-mgmt-server   eth0                      eth      up         default          MTU:1500                            2d:19h:6m:45s
oob-mgmt-server   eth1                      eth      up         default          MTU:1500                            2d:19h:6m:45s
oob-mgmt-server   eth2                      eth      up         default          LLDP: leaf01:swp44, MTU: 1500       2d:3h:54m:33s
oob-mgmt-server   eth3                      eth      up         default          LLDP: leaf02:swp44, MTU: 1500       2d:3h:54m:33s
oob-mgmt-server   lo                        loopback up         default          MTU:65536                           2d:19h:6m:45s
server01          cbr0                      bridge   up         default          Members: , Root Bridge: No Info,    1h:37m:44s
                                                                                 Root port No Info, MTU: 1500
server01          eth0                      eth      up         default          MTU:1500                            2d:18h:57m:18s
server01          eth1                      eth      up         default          LLDP: leaf01:swp1, MTU: 9000        2d:18h:57m:18s
server01          eth2                      eth      up         default          LLDP: leaf02:swp1, MTU: 9000        2d:18h:57m:18s
server01          lo                        loopback up         default          MTU:65536                           2d:18h:57m:18s
server02          cbr0                      bridge   up         default          Members: , Root Bridge: No Info,    1h:37m:43s
                                                                                 Root port No Info, MTU: 1500
server02          eth0                      eth      up         default          MTU:1500                            2d:18h:57m:18s
server02          eth1                      eth      up         default          LLDP: leaf01:swp2, MTU: 9000        2d:18h:57m:18s
server02          eth2                      eth      up         default          LLDP: leaf02:swp2, MTU: 9000        2d:18h:57m:18s
server02          lo                        loopback up         default          MTU:65536                           2d:18h:57m:18s
server03          cbr0                      bridge   up         default          Members: , Root Bridge: No Info,    1h:37m:46s
                                                                                 Root port No Info, MTU: 1500
server03          eth0                      eth      up         default          MTU:1500                            2d:18h:57m:17s
server03          eth1                      eth      up         default          LLDP: leaf03:swp1, MTU: 9000        2d:18h:57m:17s
server03          eth2                      eth      up         default          LLDP: leaf04:swp1, MTU: 9000        2d:18h:57m:17s
server03          lo                        loopback up         default          MTU:65536                           2d:18h:57m:17s
server04          cbr0                      bridge   up         default          Members: , Root Bridge: No Info,    1h:37m:46s
                                                                                 Root port No Info, MTU: 1500
server04          eth0                      eth      up         default          MTU:1500                            2d:18h:57m:17s
server04          eth1                      eth      up         default          LLDP: leaf03:swp2, MTU: 9000        2d:18h:57m:17s
server04          eth2                      eth      up         default          LLDP: leaf04:swp2, MTU: 9000        2d:18h:57m:17s
server04          lo                        loopback up         default          MTU:65536                           2d:18h:57m:17s
spine01           eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:46s
spine01           lo                        loopback up         default          MTU:65536                           2d:19h:3m:46s
spine01           mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:52s
                                                                                 Members: eth0
spine01           swp1                      swp      up         default          LLDP: leaf01:swp51, MTU: 9000       2d:19h:3m:11s
spine01           swp2                      swp      up         default          LLDP: leaf02:swp51, MTU: 9000       2d:19h:3m:11s
spine01           swp3                      swp      up         default          LLDP: leaf03:swp51, MTU: 9000       2d:19h:3m:11s
spine01           swp31                     swp      down       default          MTU:1500                            2d:19h:3m:46s
spine01           swp32                     swp      down       default          MTU:1500                            2d:19h:3m:46s
spine01           swp4                      swp      up         default          LLDP: leaf04:swp51, MTU: 9000       2d:19h:3m:11s
spine02           eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:46s
spine02           lo                        loopback up         default          MTU:65536                           2d:19h:3m:46s
spine02           mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:41s
                                                                                 Members: eth0
spine02           swp1                      swp      up         default          LLDP: leaf01:swp52, MTU: 9000       2d:19h:3m:10s
spine02           swp2                      swp      up         default          LLDP: leaf02:swp52, MTU: 9000       2d:19h:3m:11s
spine02           swp3                      swp      up         default          LLDP: leaf03:swp52, MTU: 9000       2d:19h:3m:11s
spine02           swp31                     swp      down       default          MTU:1500                            2d:19h:3m:46s
spine02           swp32                     swp      down       default          MTU:1500                            2d:19h:3m:46s
spine02           swp4                      swp      up         default          LLDP: leaf04:swp52, MTU: 9000       2d:19h:3m:10s

```
```

The following commands contain keyword(s) 'show', 'interfaces'

    netq <hostname> show docker container adjacent interfaces <remote-physical-interface> [json]
    netq <hostname> show docker container adjacent interfaces <remote-physical-interface> around <text-time> [json]
    netq [<hostname>] show interfaces [<remote-interface>] [count] [json]
    netq [<hostname>] show interfaces [<remote-interface>] around <text-time> [count] [json]
    netq [<hostname>] show interfaces [<remote-interface>] changes [json]
    netq [<hostname>] show interfaces [<remote-interface>] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show interfaces [<remote-interface>] state <remote-interface-state> [count] [json]
    netq [<hostname>] show interfaces [<remote-interface>] state <remote-interface-state> around <text-time> [count] [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] [peer] [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] [peer] around <text-time> [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] [peer] model <module-model> [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] [peer] model <module-model> around <text-time> [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] [peer] module [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] [peer] module around <text-time> [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] [peer] vendor <module-vendor> [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] [peer] vendor <module-vendor> around <text-time> [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] changes [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] model <module-model> changes [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] model <module-model> changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] module changes [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] module changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] vendor <module-vendor> changes [json]
    netq [<hostname>] show interfaces physical [<physical-port>] [empty|plugged] vendor <module-vendor> changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) [count] [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) around <text-time> [count] [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) changes [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) changes between <text-time> and <text-endtime> [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) state <remote-interface-state> [count] [json]
    netq [<hostname>] show interfaces type (bond|bridge|eth|loopback|macvlan|swp|vlan|vrf|vxlan) state <remote-interface-state> around <text-time> [count] [json]


Unable to find command netq show interfaces --help


Matching link records:
Hostname          Interface                 Type     State      VRF              Details                             Last Changed
----------------- ------------------------- -------- ---------- ---------------- ----------------------------------- ----------------
leaf01            eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:46s
leaf01            lo                        loopback up         default          MTU:65536                           2d:19h:3m:46s
leaf01            mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:54s
                                                                                 Members: eth0
leaf01            swp1                      swp      up         default          LLDP: server01:eth1, MTU: 9000      2d:19h:3m:38s
leaf01            swp2                      swp      up         default          LLDP: server02:eth1, MTU: 9000      2d:19h:3m:38s
leaf01            swp44                     swp      up         default          LLDP: oob-mgmt-server:eth2,         2d:19h:3m:22s
                                                                                 MTU: 9000
leaf01            swp45                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp46                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp47                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp48                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp49                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp50                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf01            swp51                     swp      up         default          LLDP: spine01:swp1, MTU: 9000       2d:19h:3m:38s
leaf01            swp52                     swp      up         default          LLDP: spine02:swp1, MTU: 9000       2d:19h:3m:38s
leaf02            eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:46s
leaf02            lo                        loopback up         default          MTU:65536                           2d:19h:3m:46s
leaf02            mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:52s
                                                                                 Members: eth0
leaf02            swp1                      swp      up         default          LLDP: server01:eth2, MTU: 9000      2d:19h:3m:38s
leaf02            swp2                      swp      up         default          LLDP: server02:eth2, MTU: 9000      2d:19h:3m:38s
leaf02            swp44                     swp      up         default          LLDP: oob-mgmt-server:eth3,         2d:19h:3m:26s
                                                                                 MTU: 9000
leaf02            swp45                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp46                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp47                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp48                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp49                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp50                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf02            swp51                     swp      up         default          LLDP: spine01:swp2, MTU: 9000       2d:19h:3m:38s
leaf02            swp52                     swp      up         default          LLDP: spine02:swp2, MTU: 9000       2d:19h:3m:38s
leaf03            eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:46s
leaf03            lo                        loopback up         default          MTU:65536                           2d:19h:3m:46s
leaf03            mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:52s
                                                                                 Members: eth0
leaf03            swp1                      swp      up         default          LLDP: server03:eth1, MTU: 9000      2d:19h:3m:37s
leaf03            swp2                      swp      up         default          LLDP: server04:eth1, MTU: 9000      2d:19h:3m:37s
leaf03            swp45                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp46                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp47                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp48                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp49                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp50                     swp      down       default          MTU:1500                            2d:19h:3m:46s
leaf03            swp51                     swp      up         default          LLDP: spine01:swp3, MTU: 9000       2d:19h:3m:38s
leaf03            swp52                     swp      up         default          LLDP: spine02:swp3, MTU: 9000       2d:19h:3m:37s
leaf04            eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:45s
leaf04            lo                        loopback up         default          MTU:65536                           2d:19h:3m:45s
leaf04            mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:54s
                                                                                 Members: eth0
leaf04            swp1                      swp      up         default          LLDP: server03:eth2, MTU: 9000      2d:19h:3m:38s
leaf04            swp2                      swp      up         default          LLDP: server04:eth2, MTU: 9000      2d:19h:3m:38s
leaf04            swp45                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp46                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp47                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp48                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp49                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp50                     swp      down       default          MTU:1500                            2d:19h:3m:45s
leaf04            swp51                     swp      up         default          LLDP: spine01:swp4, MTU: 9000       2d:19h:3m:38s
leaf04            swp52                     swp      up         default          LLDP: spine02:swp4, MTU: 9000       2d:19h:3m:38s
oob-mgmt-server   docker0                   bridge   down       default          Members: , Root Bridge: No Info,    1h:37m:52s
                                                                                 Root port No Info, MTU: 1500
oob-mgmt-server   eth0                      eth      up         default          MTU:1500                            2d:19h:6m:45s
oob-mgmt-server   eth1                      eth      up         default          MTU:1500                            2d:19h:6m:45s
oob-mgmt-server   eth2                      eth      up         default          LLDP: leaf01:swp44, MTU: 1500       2d:3h:54m:33s
oob-mgmt-server   eth3                      eth      up         default          LLDP: leaf02:swp44, MTU: 1500       2d:3h:54m:33s
oob-mgmt-server   lo                        loopback up         default          MTU:65536                           2d:19h:6m:45s
server01          cbr0                      bridge   up         default          Members: , Root Bridge: No Info,    1h:37m:44s
                                                                                 Root port No Info, MTU: 1500
server01          eth0                      eth      up         default          MTU:1500                            2d:18h:57m:18s
server01          eth1                      eth      up         default          LLDP: leaf01:swp1, MTU: 9000        2d:18h:57m:18s
server01          eth2                      eth      up         default          LLDP: leaf02:swp1, MTU: 9000        2d:18h:57m:18s
server01          lo                        loopback up         default          MTU:65536                           2d:18h:57m:18s
server02          cbr0                      bridge   up         default          Members: , Root Bridge: No Info,    1h:37m:43s
                                                                                 Root port No Info, MTU: 1500
server02          eth0                      eth      up         default          MTU:1500                            2d:18h:57m:18s
server02          eth1                      eth      up         default          LLDP: leaf01:swp2, MTU: 9000        2d:18h:57m:18s
server02          eth2                      eth      up         default          LLDP: leaf02:swp2, MTU: 9000        2d:18h:57m:18s
server02          lo                        loopback up         default          MTU:65536                           2d:18h:57m:18s
server03          cbr0                      bridge   up         default          Members: , Root Bridge: No Info,    1h:37m:46s
                                                                                 Root port No Info, MTU: 1500
server03          eth0                      eth      up         default          MTU:1500                            2d:18h:57m:17s
server03          eth1                      eth      up         default          LLDP: leaf03:swp1, MTU: 9000        2d:18h:57m:17s
server03          eth2                      eth      up         default          LLDP: leaf04:swp1, MTU: 9000        2d:18h:57m:17s
server03          lo                        loopback up         default          MTU:65536                           2d:18h:57m:17s
server04          cbr0                      bridge   up         default          Members: , Root Bridge: No Info,    1h:37m:46s
                                                                                 Root port No Info, MTU: 1500
server04          eth0                      eth      up         default          MTU:1500                            2d:18h:57m:17s
server04          eth1                      eth      up         default          LLDP: leaf03:swp2, MTU: 9000        2d:18h:57m:17s
server04          eth2                      eth      up         default          LLDP: leaf04:swp2, MTU: 9000        2d:18h:57m:17s
server04          lo                        loopback up         default          MTU:65536                           2d:18h:57m:17s
spine01           eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:46s
spine01           lo                        loopback up         default          MTU:65536                           2d:19h:3m:46s
spine01           mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:52s
                                                                                 Members: eth0
spine01           swp1                      swp      up         default          LLDP: leaf01:swp51, MTU: 9000       2d:19h:3m:11s
spine01           swp2                      swp      up         default          LLDP: leaf02:swp51, MTU: 9000       2d:19h:3m:11s
spine01           swp3                      swp      up         default          LLDP: leaf03:swp51, MTU: 9000       2d:19h:3m:11s
spine01           swp31                     swp      down       default          MTU:1500                            2d:19h:3m:46s
spine01           swp32                     swp      down       default          MTU:1500                            2d:19h:3m:46s
spine01           swp4                      swp      up         default          LLDP: leaf04:swp51, MTU: 9000       2d:19h:3m:11s
spine02           eth0                      eth      up         mgmt             MTU:1500                            2d:19h:3m:46s
spine02           lo                        loopback up         default          MTU:65536                           2d:19h:3m:46s
spine02           mgmt                      vrf      up                          table: 1001, MTU: 65536,            1h:37m:41s
                                                                                 Members: eth0
spine02           swp1                      swp      up         default          LLDP: leaf01:swp52, MTU: 9000       2d:19h:3m:10s
spine02           swp2                      swp      up         default          LLDP: leaf02:swp52, MTU: 9000       2d:19h:3m:11s
spine02           swp3                      swp      up         default          LLDP: leaf03:swp52, MTU: 9000       2d:19h:3m:11s
spine02           swp31                     swp      down       default          MTU:1500                            2d:19h:3m:46s
spine02           swp32                     swp      down       default          MTU:1500                            2d:19h:3m:46s
spine02           swp4                      swp      up         default          LLDP: leaf04:swp52, MTU: 9000       2d:19h:3m:10s

```
## netq check interfaces
```

[91mChecked Nodes: 11, Failed Nodes: 8[0m
[91mChecked Ports: 76, Failed Ports: 16, Unverified Ports: 36[0m
Hostname          Interface                 Peer Hostname     Peer Interface            Message
----------------- ------------------------- ----------------- ------------------------- -----------------------------------
[91mleaf01           [0m [91mswp1                     [0m [91mserver01         [0m [91meth1                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf01           [0m [91mswp2                     [0m [91mserver02         [0m [91meth1                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf02           [0m [91mswp1                     [0m [91mserver01         [0m [91meth2                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf02           [0m [91mswp2                     [0m [91mserver02         [0m [91meth2                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf03           [0m [91mswp1                     [0m [91mserver03         [0m [91meth1                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf03           [0m [91mswp2                     [0m [91mserver04         [0m [91meth1                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf04           [0m [91mswp1                     [0m [91mserver03         [0m [91meth2                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf04           [0m [91mswp2                     [0m [91mserver04         [0m [91meth2                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mserver01         [0m [91meth1                     [0m [91mleaf01           [0m [91mswp1                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver01         [0m [91meth2                     [0m [91mleaf02           [0m [91mswp1                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver02         [0m [91meth1                     [0m [91mleaf01           [0m [91mswp2                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver02         [0m [91meth2                     [0m [91mleaf02           [0m [91mswp2                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver03         [0m [91meth1                     [0m [91mleaf03           [0m [91mswp1                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver03         [0m [91meth2                     [0m [91mleaf04           [0m [91mswp1                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver04         [0m [91meth1                     [0m [91mleaf03           [0m [91mswp2                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver04         [0m [91meth2                     [0m [91mleaf04           [0m [91mswp2                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m

```
```

The following commands contain keyword(s) 'check', 'interfaces'

    netq check interfaces <physical-hostname> <physical-port> and <peer-physical-hostname> <peer-physical-port> [json]
    netq check interfaces <physical-hostname> <physical-port> and <peer-physical-hostname> <peer-physical-port> around <text-time> [json]
    netq check interfaces [unverified] <physical-hostname> <physical-port> [json]
    netq check interfaces [unverified] <physical-hostname> <physical-port> around <text-time> [json]
    netq check interfaces [unverified] <physical-hostname> [json]
    netq check interfaces [unverified] <physical-hostname> around <text-time> [json]
    netq check interfaces [unverified] [json]
    netq check interfaces [unverified] around <text-time> [json]


Unable to find command netq check interfaces --help

[91mChecked Nodes: 11, Failed Nodes: 8[0m
[91mChecked Ports: 76, Failed Ports: 16, Unverified Ports: 36[0m
Hostname          Interface                 Peer Hostname     Peer Interface            Message
----------------- ------------------------- ----------------- ------------------------- -----------------------------------
[91mleaf01           [0m [91mswp1                     [0m [91mserver01         [0m [91meth1                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf01           [0m [91mswp2                     [0m [91mserver02         [0m [91meth1                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf02           [0m [91mswp1                     [0m [91mserver01         [0m [91meth2                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf02           [0m [91mswp2                     [0m [91mserver02         [0m [91meth2                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf03           [0m [91mswp1                     [0m [91mserver03         [0m [91meth1                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf03           [0m [91mswp2                     [0m [91mserver04         [0m [91meth1                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf04           [0m [91mswp1                     [0m [91mserver03         [0m [91meth2                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mleaf04           [0m [91mswp2                     [0m [91mserver04         [0m [91meth2                     [0m [91mSpeed mismatch (1G, Unknown)       [0m
[91mserver01         [0m [91meth1                     [0m [91mleaf01           [0m [91mswp1                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver01         [0m [91meth2                     [0m [91mleaf02           [0m [91mswp1                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver02         [0m [91meth1                     [0m [91mleaf01           [0m [91mswp2                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver02         [0m [91meth2                     [0m [91mleaf02           [0m [91mswp2                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver03         [0m [91meth1                     [0m [91mleaf03           [0m [91mswp1                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver03         [0m [91meth2                     [0m [91mleaf04           [0m [91mswp1                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver04         [0m [91meth1                     [0m [91mleaf03           [0m [91mswp2                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m
[91mserver04         [0m [91meth2                     [0m [91mleaf04           [0m [91mswp2                     [0m [91mSpeed mismatch (Unknown, 1G)       [0m

```
## redis-cli info memory
```

# Memory
used_memory:6402256
used_memory_human:6.11M
used_memory_rss:9211904
used_memory_rss_human:8.79M
used_memory_peak:6549888
used_memory_peak_human:6.25M
total_system_memory:10395496448
total_system_memory_human:9.68G
used_memory_lua:69632
used_memory_lua_human:68.00K
maxmemory:6237297868
maxmemory_human:5.81G
maxmemory_policy:noeviction
mem_fragmentation_ratio:1.44
mem_allocator:jemalloc-4.0.3

```
```

ERR syntax error

```
## cat /etc/cumulus/datapath/monitor.conf
```

# Copyright 2017 Cumulus Networks Inc, all rights reserved
##
# /etc/cumulus/datapath/monitor.conf
#

# datapath state monitor
# -- port_set: e.g. swp1-swp50
# -- stat_type can be one of: (queue length) histogram, buffer, packet, packet_extended, or packet_all
# -- trigger_type can be one of: timer
# -- if trigger_type is not specified, the port group can be triggered via a 'collect' action
# -- timer: can be set to: 1s..60s or 1m..60m or 1h..24h or 1d..7d
#
# -- histogram stats require:
# -- cos_list
# -- histogram.minimum_bytes_boundary
# -- histogram.histogram_size_bytes
# -- histogram.sample_time_ns
#
# -- You can configure one or more actions to take after collecting
#    the data.  Actions can include
#    -- snapshot (write to a file),
#    -- log (write a message to /var/log/syslog), and
#    -- collect (read more stats)
#    Each action can be triggered by a statistic meeting
#    a configured threshold:  triggers can include
#    -- queue length, as measured by a histogram
#    -- packet drops due to packet buffer congestion
#    -- packet drops due to errors
#    A 'collect' action requires a port group name to designate
#    the stat collection configuration.
#
#    If no trigger is configured for an action, the action
#    will happen unconditionally.

# no monitoring is configured
monitor.port_group_list = []

# ----------------------------------------------------------------------
#
# Example monitor configuration
#
# monitor.port_group_list = [discards_pg,histogram_pg,all_packet_pg,buffers_pg]

# The queue length histograms are collected every second
# and the results are written to a snapshot file.
# Sixty-four snapshot files will be maintained.
# monitor.histogram_pg.port_set            = swp1-swp50
# monitor.histogram_pg.stat_type           = histogram
# monitor.histogram_pg.cos_list            = [0]
# monitor.histogram_pg.trigger_type        = timer
# monitor.histogram_pg.timer               = 1s
# monitor.histogram_pg.action_list         = [snapshot,collect,log]
# monitor.histogram_pg.snapshot.file       = /var/lib/cumulus/histogram_stats
# monitor.histogram_pg.snapshot.file_count = 64
# monitor.histogram_pg.histogram.minimum_bytes_boundary =   960
# monitor.histogram_pg.histogram.histogram_size_bytes   = 12288
# monitor.histogram_pg.histogram.sample_time_ns         =  1024
# monitor.histogram_pg.log.queue_bytes     = 500
# monitor.histogram_pg.collect.queue_bytes = 500
# monitor.histogram_pg.collect.port_group_list  = [buffers_pg,all_packet_pg]

# The buffer occupancy counters are collected when the
# histogram_pg monitor triggers the collect action
# monitor.buffers_pg.port_set              = swp1-swp50
# monitor.buffers_pg.stat_type             = buffer
# monitor.buffers_pg.action_list           = [snapshot]
# monitor.buffers_pg.snapshot.file         = /var/lib/cumulus/buffer_stats
# monitor.buffers_pg.snapshot.file_count   = 8

# All per-port packet counters are collected when the
# histogram_pg monitor triggers the collect action
# monitor.all_packet_pg.port_set              = swp1-swp50
# monitor.all_packet_pg.stat_type             = packet_all
# monitor.all_packet_pg.action_list           = [snapshot]
# monitor.all_packet_pg.snapshot.file         = /var/lib/cumulus/all_packet_stats
# monitor.all_packet_pg.snapshot.file_count   = 8

# The packet discard counters are collected every two minutes
# The snapshot will be written if any discard counter is greater
# than 100, and a log message will be written out at the same
# drop threshold.
# monitor.discards_pg.port_set                       = swp1-swp50
# monitor.discards_pg.stat_type                      = packet
# monitor.discards_pg.action_list                    = [snapshot,log]
# monitor.discards_pg.trigger_type                   = timer
# monitor.discards_pg.timer                          = 2s  # debugging
# monitor.discards_pg.log.packet_error_drops         = 100
# monitor.discards_pg.snapshot.packet_error_drops    = 100
# monitor.discards_pg.snapshot.file                  = /var/lib/cumulus/discard_stats
# monitor.discards_pg.snapshot.file_count            = 16



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

# Copyright 2017 Cumulus Networks Inc, all rights reserved
##
# /etc/cumulus/datapath/monitor.conf
#

# datapath state monitor
# -- port_set: e.g. swp1-swp50
# -- stat_type can be one of: (queue length) histogram, buffer, packet, packet_extended, or packet_all
# -- trigger_type can be one of: timer
# -- if trigger_type is not specified, the port group can be triggered via a 'collect' action
# -- timer: can be set to: 1s..60s or 1m..60m or 1h..24h or 1d..7d
#
# -- histogram stats require:
# -- cos_list
# -- histogram.minimum_bytes_boundary
# -- histogram.histogram_size_bytes
# -- histogram.sample_time_ns
#
# -- You can configure one or more actions to take after collecting
#    the data.  Actions can include
#    -- snapshot (write to a file),
#    -- log (write a message to /var/log/syslog), and
#    -- collect (read more stats)
#    Each action can be triggered by a statistic meeting
#    a configured threshold:  triggers can include
#    -- queue length, as measured by a histogram
#    -- packet drops due to packet buffer congestion
#    -- packet drops due to errors
#    A 'collect' action requires a port group name to designate
#    the stat collection configuration.
#
#    If no trigger is configured for an action, the action
#    will happen unconditionally.

# no monitoring is configured
monitor.port_group_list = []

# ----------------------------------------------------------------------
#
# Example monitor configuration
#
# monitor.port_group_list = [discards_pg,histogram_pg,all_packet_pg,buffers_pg]

# The queue length histograms are collected every second
# and the results are written to a snapshot file.
# Sixty-four snapshot files will be maintained.
# monitor.histogram_pg.port_set            = swp1-swp50
# monitor.histogram_pg.stat_type           = histogram
# monitor.histogram_pg.cos_list            = [0]
# monitor.histogram_pg.trigger_type        = timer
# monitor.histogram_pg.timer               = 1s
# monitor.histogram_pg.action_list         = [snapshot,collect,log]
# monitor.histogram_pg.snapshot.file       = /var/lib/cumulus/histogram_stats
# monitor.histogram_pg.snapshot.file_count = 64
# monitor.histogram_pg.histogram.minimum_bytes_boundary =   960
# monitor.histogram_pg.histogram.histogram_size_bytes   = 12288
# monitor.histogram_pg.histogram.sample_time_ns         =  1024
# monitor.histogram_pg.log.queue_bytes     = 500
# monitor.histogram_pg.collect.queue_bytes = 500
# monitor.histogram_pg.collect.port_group_list  = [buffers_pg,all_packet_pg]

# The buffer occupancy counters are collected when the
# histogram_pg monitor triggers the collect action
# monitor.buffers_pg.port_set              = swp1-swp50
# monitor.buffers_pg.stat_type             = buffer
# monitor.buffers_pg.action_list           = [snapshot]
# monitor.buffers_pg.snapshot.file         = /var/lib/cumulus/buffer_stats
# monitor.buffers_pg.snapshot.file_count   = 8

# All per-port packet counters are collected when the
# histogram_pg monitor triggers the collect action
# monitor.all_packet_pg.port_set              = swp1-swp50
# monitor.all_packet_pg.stat_type             = packet_all
# monitor.all_packet_pg.action_list           = [snapshot]
# monitor.all_packet_pg.snapshot.file         = /var/lib/cumulus/all_packet_stats
# monitor.all_packet_pg.snapshot.file_count   = 8

# The packet discard counters are collected every two minutes
# The snapshot will be written if any discard counter is greater
# than 100, and a log message will be written out at the same
# drop threshold.
# monitor.discards_pg.port_set                       = swp1-swp50
# monitor.discards_pg.stat_type                      = packet
# monitor.discards_pg.action_list                    = [snapshot,log]
# monitor.discards_pg.trigger_type                   = timer
# monitor.discards_pg.timer                          = 2s  # debugging
# monitor.discards_pg.log.packet_error_drops         = 100
# monitor.discards_pg.snapshot.packet_error_drops    = 100
# monitor.discards_pg.snapshot.file                  = /var/lib/cumulus/discard_stats
# monitor.discards_pg.snapshot.file_count            = 16



```
## cat /etc/default/networking
```

#
#
# Parameters for the networking service
#
#

# Change the below to yes if you want verbose logging to be enabled
VERBOSE="no"

# Change the below to yes if you want debug logging to be enabled
DEBUG="no"

# Change the below to yes if you want logging to go to syslog
SYSLOG="no"

# Exclude interfaces
EXCLUDE_INTERFACES=

# Set to 'yes' if you want to skip ifdown during system reboot
# and shutdown. This is of interest in large scale interface
# deployments where you dont want to wait for interface
# deconfiguration to speed up shutdown/reboot
SKIP_DOWN_AT_SYSRESET="yes"

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
#
# Parameters for the networking service
#
#

# Change the below to yes if you want verbose logging to be enabled
VERBOSE="no"

# Change the below to yes if you want debug logging to be enabled
DEBUG="no"

# Change the below to yes if you want logging to go to syslog
SYSLOG="no"

# Exclude interfaces
EXCLUDE_INTERFACES=

# Set to 'yes' if you want to skip ifdown during system reboot
# and shutdown. This is of interest in large scale interface
# deployments where you dont want to wait for interface
# deconfiguration to speed up shutdown/reboot
SKIP_DOWN_AT_SYSRESET="yes"

```
## cl-acltool -L
```

usage: cl-acltool [-h]
                  (-i | -F {all,ip,ip6,eb} | -Z {all,ip,ip6,eb} | -L {all,ip,ip6,eb} | -V)
                  [-p POLICY_FILE] [-P POLICY_DIR] [-n] [-N] [-v] [-x]
                  [--last-good]
cl-acltool: error: argument -L/--list: expected one argument

```
```

nohup: failed to run command ‘cl-acltool’: No such file or directory

```
## iptables -L
```

Chain INPUT (policy ACCEPT)
target     prot opt source               destination         
DROP       all  --  240.0.0.0/5          anywhere            
DROP       all  --  loopback/8           anywhere            
DROP       all  --  base-address.mcast.net/4  anywhere            
DROP       all  --  255.255.255.255      anywhere            
SETCLASS   udp  --  anywhere             anywhere             udp dpt:3785 SETCLASS  class:7
POLICE     udp  --  anywhere             anywhere             udp dpt:3785 POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   udp  --  anywhere             anywhere             udp dpt:3784 SETCLASS  class:7
POLICE     udp  --  anywhere             anywhere             udp dpt:3784 POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   udp  --  anywhere             anywhere             udp dpt:4784 SETCLASS  class:7
POLICE     udp  --  anywhere             anywhere             udp dpt:4784 POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   ospf --  anywhere             anywhere             SETCLASS  class:7
POLICE     ospf --  anywhere             anywhere             POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   pim  --  anywhere             anywhere             SETCLASS  class:6
POLICE     pim  --  anywhere             anywhere             POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   tcp  --  anywhere             anywhere             tcp dpt:639 SETCLASS  class:6
POLICE     tcp  --  anywhere             anywhere             tcp dpt:639 POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   tcp  --  anywhere             anywhere             tcp spt:639 SETCLASS  class:6
POLICE     tcp  --  anywhere             anywhere             tcp spt:639 POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   tcp  --  anywhere             anywhere             tcp dpt:bgp SETCLASS  class:7
POLICE     tcp  --  anywhere             anywhere             tcp dpt:bgp POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   tcp  --  anywhere             anywhere             tcp spt:bgp SETCLASS  class:7
POLICE     tcp  --  anywhere             anywhere             tcp spt:bgp POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   tcp  --  anywhere             anywhere             tcp dpt:5342 SETCLASS  class:7
POLICE     tcp  --  anywhere             anywhere             tcp dpt:5342 POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   tcp  --  anywhere             anywhere             tcp spt:5342 SETCLASS  class:7
POLICE     tcp  --  anywhere             anywhere             tcp spt:5342 POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   icmp --  anywhere             anywhere             SETCLASS  class:2
POLICE     icmp --  anywhere             anywhere             POLICE  mode:pkt rate:100 burst:40
SETCLASS   udp  --  anywhere             anywhere             udp dpts:bootps:bootpc SETCLASS  class:2
POLICE     udp  --  anywhere             anywhere             udp dpt:bootps POLICE  mode:pkt rate:100 burst:100
POLICE     udp  --  anywhere             anywhere             udp dpt:bootpc POLICE  mode:pkt rate:100 burst:100
SETCLASS   tcp  --  anywhere             anywhere             tcp dpts:bootps:bootpc SETCLASS  class:2
POLICE     tcp  --  anywhere             anywhere             tcp dpt:bootps POLICE  mode:pkt rate:100 burst:100
POLICE     tcp  --  anywhere             anywhere             tcp dpt:bootpc POLICE  mode:pkt rate:100 burst:100
SETCLASS   udp  --  anywhere             anywhere             udp dpt:10001 SETCLASS  class:3
POLICE     udp  --  anywhere             anywhere             udp dpt:10001 POLICE  mode:pkt rate:2000 burst:2000
SETCLASS   igmp --  anywhere             anywhere             SETCLASS  class:6
POLICE     igmp --  anywhere             anywhere             POLICE  mode:pkt rate:300 burst:100
POLICE     all  --  anywhere             anywhere             ADDRTYPE match dst-type LOCAL POLICE  mode:pkt rate:1000 burst:1000 class:0
POLICE     all  --  anywhere             anywhere             ADDRTYPE match dst-type IPROUTER POLICE  mode:pkt rate:400 burst:100 class:0
SETCLASS   all  --  anywhere             anywhere             SETCLASS  class:0

Chain FORWARD (policy ACCEPT)
target     prot opt source               destination         
DROP       all  --  240.0.0.0/5          anywhere            
DROP       all  --  loopback/8           anywhere            
DROP       all  --  base-address.mcast.net/4  anywhere            
DROP       all  --  255.255.255.255      anywhere            

Chain OUTPUT (policy ACCEPT)
target     prot opt source               destination         

```
```

nohup: failed to run command ‘iptables’: No such file or directory

```
## ip6tables -L
```

Chain INPUT (policy ACCEPT)
target     prot opt source               destination         
ACCEPT     all      ::                   anywhere            
DROP       all      ff00::/8             anywhere            
DROP       all      ::                   anywhere            
DROP       all      ::ffff:0.0.0.0/96    anywhere            
DROP       all      localhost            anywhere            
POLICE     udp      anywhere             anywhere             udp dpt:3785 POLICE  mode:pkt rate:2000 burst:2000 class:7
POLICE     udp      anywhere             anywhere             udp dpt:3784 POLICE  mode:pkt rate:2000 burst:2000 class:7
POLICE     udp      anywhere             anywhere             udp dpt:4784 POLICE  mode:pkt rate:2000 burst:2000 class:7
POLICE     ospf     anywhere             anywhere             POLICE  mode:pkt rate:2000 burst:2000 class:7
POLICE     tcp      anywhere             anywhere             tcp dpt:bgp POLICE  mode:pkt rate:2000 burst:2000 class:7
POLICE     tcp      anywhere             anywhere             tcp spt:bgp POLICE  mode:pkt rate:2000 burst:2000 class:7
POLICE     ipv6-icmp    anywhere             anywhere             ipv6-icmp router-solicitation POLICE  mode:pkt rate:100 burst:100 class:2
POLICE     ipv6-icmp    anywhere             anywhere             ipv6-icmp router-advertisement POLICE  mode:pkt rate:500 burst:500 class:2
POLICE     ipv6-icmp    anywhere             anywhere             ipv6-icmp neighbour-solicitation POLICE  mode:pkt rate:400 burst:400 class:2
POLICE     ipv6-icmp    anywhere             anywhere             ipv6-icmp neighbour-advertisement POLICE  mode:pkt rate:400 burst:400 class:2
POLICE     ipv6-icmp    anywhere             anywhere             ipv6-icmptype 130 POLICE  mode:pkt rate:200 burst:100 class:6
POLICE     ipv6-icmp    anywhere             anywhere             ipv6-icmptype 131 POLICE  mode:pkt rate:200 burst:100 class:6
POLICE     ipv6-icmp    anywhere             anywhere             ipv6-icmptype 132 POLICE  mode:pkt rate:200 burst:100 class:6
POLICE     ipv6-icmp    anywhere             anywhere             ipv6-icmptype 143 POLICE  mode:pkt rate:200 burst:100 class:6
POLICE     ipv6-icmp    anywhere             anywhere             POLICE  mode:pkt rate:64 burst:40 class:2
POLICE     udp      anywhere             anywhere             udp dpts:dhcpv6-client:dhcpv6-server POLICE  mode:pkt rate:100 burst:100 class:2
POLICE     tcp      anywhere             anywhere             tcp dpts:dhcpv6-client:dhcpv6-server POLICE  mode:pkt rate:100 burst:100 class:2
POLICE     all      anywhere             anywhere             ADDRTYPE match dst-type LOCAL POLICE  mode:pkt rate:1000 burst:1000 class:0
POLICE     all      anywhere             anywhere             ADDRTYPE match dst-type IPROUTER POLICE  mode:pkt rate:400 burst:100 class:0
SETCLASS   all      anywhere             anywhere             SETCLASS  class:0

Chain FORWARD (policy ACCEPT)
target     prot opt source               destination         
DROP       all      ff00::/8             anywhere            
DROP       all      ::                   anywhere            
DROP       all      ::ffff:0.0.0.0/96    anywhere            
DROP       all      localhost            anywhere            

Chain OUTPUT (policy ACCEPT)
target     prot opt source               destination         

```
```

nohup: failed to run command ‘ip6tables’: No such file or directory

```
## ebtables -L
```

Bridge table: filter

Bridge chain: INPUT, entries: 17, policy: ACCEPT
-d BGA -i swp+ -j setclass --class 7 
-d BGA -j police --set-mode pkt --set-rate 2000 --set-burst 2000 
-d 1:80:c2:0:0:2 -i swp+ -j setclass --class 7 
-d 1:80:c2:0:0:2 -j police --set-mode pkt --set-rate 2000 --set-burst 2000 
-d 1:80:c2:0:0:e -i swp+ -j setclass --class 6 
-d 1:80:c2:0:0:e -j police --set-mode pkt --set-rate 200 --set-burst 200 
-d 1:0:c:cc:cc:cc -i swp+ -j setclass --class 6 
-d 1:0:c:cc:cc:cc -j police --set-mode pkt --set-rate 200 --set-burst 200 
-p ARP -i swp+ -j setclass --class 2 
-p ARP -j police --set-mode pkt --set-rate 400 --set-burst 100 
-d 1:0:c:cc:cc:cd -i swp+ -j setclass --class 7 
-d 1:0:c:cc:cc:cd -j police --set-mode pkt --set-rate 2000 --set-burst 2000 
-p IPv4 -i swp+ -j ACCEPT 
-p IPv6 -i swp+ -j ACCEPT 
-i swp+ -j setclass --class 0 
-p IPv4 -d 1:0:5e:0:0:0/ff:ff:ff:80:0:0 -j police --set-mode pkt --set-rate 100 --set-burst 100 
-j police --set-mode pkt --set-rate 100 --set-burst 100 

Bridge chain: FORWARD, entries: 0, policy: ACCEPT

Bridge chain: OUTPUT, entries: 0, policy: ACCEPT

```
```

nohup: failed to run command ‘ebtables’: No such file or directory

```
## netstat -l
```

Active Internet connections (only servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State      
tcp        0      0 *:5000                  *:*                     LISTEN     
tcp        0      0 localhost:zebra         *:*                     LISTEN     
tcp        0      0 *:6379                  *:*                     LISTEN     
tcp        0      0 *:26379                 *:*                     LISTEN     
tcp        0      0 localhost:bgpd          *:*                     LISTEN     
tcp        0      0 *:9999                  *:*                     LISTEN     
tcp        0      0 *:bgp                   *:*                     LISTEN     
tcp        0      0 *:ssh                   *:*                     LISTEN     
tcp        0      0 localhost:omniorb       *:*                     LISTEN     
tcp        0      0 *:1337                  *:*                     LISTEN     
tcp6       0      0 [::]:2375               [::]:*                  LISTEN     
tcp6       0      0 [::]:9000               [::]:*                  LISTEN     
tcp6       0      0 [::]:6379               [::]:*                  LISTEN     
tcp6       0      0 [::]:26379              [::]:*                  LISTEN     
tcp6       0      0 [::]:http-alt           [::]:*                  LISTEN     
tcp6       0      0 [::]:bgp                [::]:*                  LISTEN     
tcp6       0      0 [::]:8086               [::]:*                  LISTEN     
tcp6       0      0 [::]:ssh                [::]:*                  LISTEN     
tcp6       0      0 [::]:1337               [::]:*                  LISTEN     
udp        0      0 *:3784                  *:*                                
udp        0      0 *:3785                  *:*                                
udp        0      0 *:4784                  *:*                                
udp        0      0 *:13019                 *:*                                
udp        0      0 *:bootps                *:*                                
udp        0      0 10.255.0.1:ntp          *:*                                
udp        0      0 localhost:ntp           *:*                                
udp        0      0 *:ntp                   *:*                                
udp6       0      0 [::]:3784               [::]:*                             
udp6       0      0 [::]:4784               [::]:*                             
udp6       0      0 [::]:6806               [::]:*                             
udp6       0      0 fe80::4638:39ff:fe0:ntp [::]:*                             
udp6       0      0 localhost:ntp           [::]:*                             
udp6       0      0 [::]:ntp                [::]:*                             
raw        0      0 *:icmp                  *:*                     7          
raw6       0      0 [::]:ipv6-icmp          [::]:*                  7          
Active UNIX domain sockets (only servers)
Proto RefCnt Flags       Type       State         I-Node   Path
unix  2      [ ACC ]     STREAM     LISTENING     13568    /var/run/mcelog-client
unix  2      [ ACC ]     STREAM     LISTENING     20108    /var/run/netqd/uds
unix  2      [ ACC ]     STREAM     LISTENING     18203    /run/docker/libnetwork/c77bb075b7d7655ce6057f6a759a618b3d1afe738b4a9d290e73b888973eee87.sock
unix  2      [ ACC ]     STREAM     LISTENING     17077    @/containerd-shim/moby/4cc26bfbf1be6a4599c15f9b835a9f62a605488e0eb79e5b5ac857adbc200a80/shim.sock
unix  2      [ ACC ]     STREAM     LISTENING     18230    @/containerd-shim/moby/b6722ff84f52a4ea19d367de60a29506cf4f756eb9b40516b68c21a18e02b7fb/shim.sock
unix  2      [ ACC ]     STREAM     LISTENING     11328    /run/uuidd/request
unix  2      [ ACC ]     STREAM     LISTENING     11331    /var/run/docker.sock
unix  2      [ ACC ]     STREAM     LISTENING     11333    /var/run/ctsauth/pam.sock
unix  2      [ ACC ]     STREAM     LISTENING     11336    /run/acpid.socket
unix  2      [ ACC ]     STREAM     LISTENING     11338    /var/run/dbus/system_bus_socket
unix  2      [ ACC ]     STREAM     LISTENING     16730    /var/run/netqd/uds
unix  2      [ ACC ]     STREAM     LISTENING     15328    @/var/run/ptmd.socket
unix  2      [ ACC ]     STREAM     LISTENING     17114    @/containerd-shim/moby/d1342dce41740c07fd9ae88ce9a952edcf3cec36a3dd5c9546dad8c0e09f8141/shim.sock
unix  2      [ ACC ]     STREAM     LISTENING     17098    @/containerd-shim/moby/b2f5e1e9d1a2f5838473ec5f2396182ff65a4b74ba660b033f65e90b2c583c6a/shim.sock
unix  2      [ ACC ]     STREAM     LISTENING     16243    /var/run/lldpd.socket
unix  2      [ ACC ]     STREAM     LISTENING     14963    /var/run/frr/zebra.vty
unix  2      [ ACC ]     STREAM     LISTENING     16503    /var/run/docker.sock
unix  2      [ ACC ]     STREAM     LISTENING     126583   /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1
unix  2      [ ACC ]     STREAM     LISTENING     14973    /var/run/frr/bgpd.vty
unix  2      [ ACC ]     STREAM     LISTENING     126748   /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/JTw8Am_C.S8lUUiFHLlpRdKZK
unix  2      [ ACC ]     STREAM     LISTENING     14980    /var/run/frr/watchfrr.vty
unix  2      [ ACC ]     STREAM     LISTENING     17815    /var/run/docker/containerd/docker-containerd-debug.sock
unix  2      [ ACC ]     STREAM     LISTENING     17818    /var/run/docker/containerd/docker-containerd.sock
unix  2      [ ACC ]     STREAM     LISTENING     15774    /var/run/neighmgrd/uds
unix  2      [ ACC ]     STREAM     LISTENING     15777    /var/run/frr/zserv.api
unix  2      [ ACC ]     STREAM     LISTENING     17826    /var/run/docker/metrics.sock
unix  2      [ ACC ]     STREAM     LISTENING     17084    @/containerd-shim/moby/11b15c8fbacfa7624f9451cda0ac73e68f8beca6d145381655bcc2b94ad46693/shim.sock
unix  2      [ ACC ]     STREAM     LISTENING     15320    @/var/run/ptmd-quagga.socket
unix  2      [ ACC ]     STREAM     LISTENING     710      /run/systemd/private
unix  2      [ ACC ]     STREAM     LISTENING     18125    /var/run/nclu/uds
unix  2      [ ACC ]     STREAM     LISTENING     732      /run/lvm/lvmetad.socket
unix  2      [ ACC ]     SEQPACKET  LISTENING     737      /run/udev/control
unix  2      [ ACC ]     STREAM     LISTENING     740      /run/systemd/journal/stdout

```
```

usage: netstat [-vWeenNcCF] [<Af>] -r         netstat {-V|--version|-h|--help}
       netstat [-vWnNcaeol] [<Socket> ...]
       netstat { [-vWeenNac] -i | [-cWnNe] -M | -s }

        -r, --route              display routing table
        -i, --interfaces         display interface table
        -g, --groups             display multicast group memberships
        -s, --statistics         display networking statistics (like SNMP)
        -M, --masquerade         display masqueraded connections

        -v, --verbose            be verbose
        -W, --wide               don't truncate IP addresses
        -n, --numeric            don't resolve names
        --numeric-hosts          don't resolve host names
        --numeric-ports          don't resolve port names
        --numeric-users          don't resolve user names
        -N, --symbolic           resolve hardware names
        -e, --extend             display other/more information
        -p, --programs           display PID/Program name for sockets
        -c, --continuous         continuous listing

        -l, --listening          display listening server sockets
        -a, --all, --listening   display all sockets (default: connected)
        -o, --timers             display timers
        -F, --fib                display Forwarding Information Base (default)
        -C, --cache              display routing cache instead of FIB

  <Socket>={-t|--tcp} {-u|--udp} {-w|--raw} {-x|--unix} --ax25 --ipx --netrom
  <AF>=Use '-6|-4' or '-A <af>' or '--<af>'; default: inet
  List of possible address families (which support routing):
    inet (DARPA Internet) inet6 (IPv6) ax25 (AMPR AX.25) 
    netrom (AMPR NET/ROM) ipx (Novell IPX) ddp (Appletalk DDP) 
    x25 (CCITT X.25) 

```
## netstat -at
```

Active Internet connections (servers and established)
Proto Recv-Q Send-Q Local Address           Foreign Address         State      
tcp        0      0 *:5000                  *:*                     LISTEN     
tcp        0      0 localhost:zebra         *:*                     LISTEN     
tcp        0      0 *:6379                  *:*                     LISTEN     
tcp        0      0 *:26379                 *:*                     LISTEN     
tcp        0      0 localhost:bgpd          *:*                     LISTEN     
tcp        0      0 *:9999                  *:*                     LISTEN     
tcp        0      0 *:bgp                   *:*                     LISTEN     
tcp        0      0 *:ssh                   *:*                     LISTEN     
tcp        0      0 localhost:omniorb       *:*                     LISTEN     
tcp        0      0 *:1337                  *:*                     LISTEN     
tcp        0      0 oob-mgmt-server:51455   oob-mgmt-server:6379    TIME_WAIT  
tcp        0      0 localhost:53439         localhost:2375          ESTABLISHED
tcp        0      0 localhost:53444         localhost:2375          ESTABLISHED
tcp        0      0 oob-mgmt-server:51045   oob-mgmt-server:6379    ESTABLISHED
tcp        0      0 10.255.0.1:1337         172-5-126-131.lig:60592 ESTABLISHED
tcp        0      0 localhost:53443         localhost:2375          ESTABLISHED
tcp        0      0 localhost:39582         localhost:6379          TIME_WAIT  
tcp        0      0 10.255.0.1:ssh          172-5-126-131.lig:60617 ESTABLISHED
tcp        0      0 oob-mgmt-server:51458   oob-mgmt-server:6379    TIME_WAIT  
tcp        0      0 oob-mgmt-server:6379    server04:56912          ESTABLISHED
tcp        0      0 oob-mgmt-server:6379    oob-mgmt-server:51045   ESTABLISHED
tcp        0      0 oob-mgmt-server:6379    spine02:56172           ESTABLISHED
tcp        0      0 oob-mgmt-server:6379    spine01:59722           ESTABLISHED
tcp        0      0 oob-mgmt-server:6379    server02:59278          ESTABLISHED
tcp        0      0 oob-mgmt-server:51453   oob-mgmt-server:6379    TIME_WAIT  
tcp        0      0 localhost:53441         localhost:2375          ESTABLISHED
tcp        0      0 oob-mgmt-server:6379    spine01:59346           ESTABLISHED
tcp        0      0 localhost:53442         localhost:2375          ESTABLISHED
tcp        0      0 localhost:53445         localhost:2375          ESTABLISHED
tcp        0      0 localhost:39581         localhost:6379          TIME_WAIT  
tcp        0      0 oob-mgmt-server:6379    leaf03:47542            ESTABLISHED
tcp        0      0 oob-mgmt-server:51456   oob-mgmt-server:6379    TIME_WAIT  
tcp        0      0 oob-mgmt-server:6379    leaf01:34884            ESTABLISHED
tcp        0      0 localhost:53440         localhost:2375          ESTABLISHED
tcp        0      0 oob-mgmt-server:51454   oob-mgmt-server:6379    TIME_WAIT  
tcp        0      0 localhost:39580         localhost:6379          TIME_WAIT  
tcp        0      0 oob-mgmt-server:6379    server03:43482          ESTABLISHED
tcp        0      0 oob-mgmt-server:6379    leaf02:48898            ESTABLISHED
tcp        0      0 oob-mgmt-server:6379    leaf04:46062            ESTABLISHED
tcp        0      0 localhost:53438         localhost:2375          ESTABLISHED
tcp        0      0 oob-mgmt-server:6379    server01:35238          ESTABLISHED
tcp        0      0 oob-mgmt-server:51459   oob-mgmt-server:6379    TIME_WAIT  
tcp        0      0 10.255.0.1:ssh          172-5-126-131.lig:60630 ESTABLISHED
tcp        0      0 oob-mgmt-server:51457   oob-mgmt-server:6379    TIME_WAIT  
tcp6       0      0 [::]:2375               [::]:*                  LISTEN     
tcp6       0      0 [::]:9000               [::]:*                  LISTEN     
tcp6       0      0 [::]:6379               [::]:*                  LISTEN     
tcp6       0      0 [::]:26379              [::]:*                  LISTEN     
tcp6       0      0 [::]:http-alt           [::]:*                  LISTEN     
tcp6       0      0 [::]:bgp                [::]:*                  LISTEN     
tcp6       0      0 [::]:8086               [::]:*                  LISTEN     
tcp6       0      0 [::]:ssh                [::]:*                  LISTEN     
tcp6       0      0 [::]:1337               [::]:*                  LISTEN     
tcp6       0      0 localhost:ssh           localhost:35072         ESTABLISHED
tcp6       0      0 localhost:2375          localhost:53439         ESTABLISHED
tcp6       0      0 localhost:2375          localhost:53445         ESTABLISHED
tcp6       0      0 localhost:2375          localhost:53443         ESTABLISHED
tcp6       0      0 fe80::4638:39ff:f:55410 fe80::4638:39ff:fe0:bgp ESTABLISHED
tcp6       0      0 localhost:2375          localhost:53444         ESTABLISHED
tcp6       0      0 fe80::4638:39ff:f:60999 fe80::4638:39ff:fe0:bgp ESTABLISHED
tcp6       0      0 localhost:2375          localhost:53442         ESTABLISHED
tcp6       0      0 localhost:2375          localhost:53438         ESTABLISHED
tcp6       0      0 localhost:2375          localhost:53441         ESTABLISHED
tcp6       0      0 localhost:2375          localhost:53440         ESTABLISHED
tcp6       0      0 localhost:35072         localhost:ssh           ESTABLISHED

```
```

usage: netstat [-vWeenNcCF] [<Af>] -r         netstat {-V|--version|-h|--help}
       netstat [-vWnNcaeol] [<Socket> ...]
       netstat { [-vWeenNac] -i | [-cWnNe] -M | -s }

        -r, --route              display routing table
        -i, --interfaces         display interface table
        -g, --groups             display multicast group memberships
        -s, --statistics         display networking statistics (like SNMP)
        -M, --masquerade         display masqueraded connections

        -v, --verbose            be verbose
        -W, --wide               don't truncate IP addresses
        -n, --numeric            don't resolve names
        --numeric-hosts          don't resolve host names
        --numeric-ports          don't resolve port names
        --numeric-users          don't resolve user names
        -N, --symbolic           resolve hardware names
        -e, --extend             display other/more information
        -p, --programs           display PID/Program name for sockets
        -c, --continuous         continuous listing

        -l, --listening          display listening server sockets
        -a, --all, --listening   display all sockets (default: connected)
        -o, --timers             display timers
        -F, --fib                display Forwarding Information Base (default)
        -C, --cache              display routing cache instead of FIB

  <Socket>={-t|--tcp} {-u|--udp} {-w|--raw} {-x|--unix} --ax25 --ipx --netrom
  <AF>=Use '-6|-4' or '-A <af>' or '--<af>'; default: inet
  List of possible address families (which support routing):
    inet (DARPA Internet) inet6 (IPv6) ax25 (AMPR AX.25) 
    netrom (AMPR NET/ROM) ipx (Novell IPX) ddp (Appletalk DDP) 
    x25 (CCITT X.25) 

```
## netstat -au
```

Active Internet connections (servers and established)
Proto Recv-Q Send-Q Local Address           Foreign Address         State      
udp        0      0 *:3784                  *:*                                
udp        0      0 *:3785                  *:*                                
udp        0      0 *:4784                  *:*                                
udp        0      0 *:13019                 *:*                                
udp        0      0 *:bootps                *:*                                
udp        0      0 10.255.0.1:ntp          *:*                                
udp        0      0 localhost:ntp           *:*                                
udp        0      0 *:ntp                   *:*                                
udp6       0      0 [::]:3784               [::]:*                             
udp6       0      0 [::]:4784               [::]:*                             
udp6       0      0 [::]:6806               [::]:*                             
udp6       0      0 fe80::4638:39ff:fe0:ntp [::]:*                             
udp6       0      0 localhost:ntp           [::]:*                             
udp6       0      0 [::]:ntp                [::]:*                             

```
```

usage: netstat [-vWeenNcCF] [<Af>] -r         netstat {-V|--version|-h|--help}
       netstat [-vWnNcaeol] [<Socket> ...]
       netstat { [-vWeenNac] -i | [-cWnNe] -M | -s }

        -r, --route              display routing table
        -i, --interfaces         display interface table
        -g, --groups             display multicast group memberships
        -s, --statistics         display networking statistics (like SNMP)
        -M, --masquerade         display masqueraded connections

        -v, --verbose            be verbose
        -W, --wide               don't truncate IP addresses
        -n, --numeric            don't resolve names
        --numeric-hosts          don't resolve host names
        --numeric-ports          don't resolve port names
        --numeric-users          don't resolve user names
        -N, --symbolic           resolve hardware names
        -e, --extend             display other/more information
        -p, --programs           display PID/Program name for sockets
        -c, --continuous         continuous listing

        -l, --listening          display listening server sockets
        -a, --all, --listening   display all sockets (default: connected)
        -o, --timers             display timers
        -F, --fib                display Forwarding Information Base (default)
        -C, --cache              display routing cache instead of FIB

  <Socket>={-t|--tcp} {-u|--udp} {-w|--raw} {-x|--unix} --ax25 --ipx --netrom
  <AF>=Use '-6|-4' or '-A <af>' or '--<af>'; default: inet
  List of possible address families (which support routing):
    inet (DARPA Internet) inet6 (IPv6) ax25 (AMPR AX.25) 
    netrom (AMPR NET/ROM) ipx (Novell IPX) ddp (Appletalk DDP) 
    x25 (CCITT X.25) 

```
## ps -ef
```

UID        PID  PPID  C STIME TTY          TIME CMD
root         1     0  0 18:06 ?        00:00:32 /sbin/init
root         2     0  0 18:06 ?        00:00:00 [kthreadd]
root         3     2  0 18:06 ?        00:00:40 [ksoftirqd/0]
root         5     2  0 18:06 ?        00:00:00 [kworker/0:0H]
root         7     2  0 18:06 ?        00:00:05 [rcu_sched]
root         8     2  0 18:06 ?        00:00:00 [rcu_bh]
root         9     2  0 18:06 ?        00:00:01 [migration/0]
root        10     2  0 18:06 ?        00:00:00 [watchdog/0]
root        11     2  0 18:06 ?        00:00:00 [watchdog/1]
root        12     2  0 18:06 ?        00:00:01 [migration/1]
root        13     2  0 18:06 ?        00:00:41 [ksoftirqd/1]
root        15     2  0 18:06 ?        00:00:00 [kworker/1:0H]
root        16     2  0 18:06 ?        00:00:00 [khelper]
root        17     2  0 18:06 ?        00:00:00 [kdevtmpfs]
root        18     2  0 18:06 ?        00:00:00 [netns]
root        19     2  0 18:06 ?        00:00:00 [perf]
root        20     2  0 18:06 ?        00:00:00 [khungtaskd]
root        21     2  0 18:06 ?        00:00:00 [writeback]
root        23     2  0 18:06 ?        00:00:00 [ksmd]
root        24     2  0 18:06 ?        00:00:00 [khugepaged]
root        25     2  0 18:06 ?        00:00:00 [crypto]
root        26     2  0 18:06 ?        00:00:00 [kintegrityd]
root        27     2  0 18:06 ?        00:00:00 [bioset]
root        28     2  0 18:06 ?        00:00:00 [kblockd]
root        29     2  0 18:06 ?        00:00:00 [ata_sff]
root        30     2  0 18:06 ?        00:00:00 [edac-poller]
root        32     2  0 18:06 ?        00:00:00 [rpciod]
root        33     2  0 18:06 ?        00:00:00 [kswapd0]
root        34     2  0 18:06 ?        00:00:00 [fsnotify_mark]
root        35     2  0 18:06 ?        00:00:00 [nfsiod]
root        44     2  0 18:06 ?        00:00:00 [kthrotld]
root        45     2  0 18:06 ?        00:00:00 [scsi_eh_0]
root        46     2  0 18:06 ?        00:00:00 [scsi_tmf_0]
root        47     2  0 18:06 ?        00:00:00 [scsi_eh_1]
root        48     2  0 18:06 ?        00:00:00 [scsi_tmf_1]
root        51     2  0 18:06 ?        00:00:00 [ipv6_addrconf]
root        52     2  0 18:06 ?        00:00:00 [deferwq]
root        89     2  0 18:06 ?        00:00:01 [kworker/1:1H]
root        91     2  0 18:06 ?        00:00:01 [kworker/0:1H]
root       103     2  0 18:06 ?        00:00:00 [bioset]
root       120     2  0 18:06 ?        00:00:00 [btrfs-worker]
root       122     2  0 18:06 ?        00:00:00 [btrfs-worker-hi]
root       123     2  0 18:06 ?        00:00:00 [btrfs-delalloc]
root       124     2  0 18:06 ?        00:00:00 [btrfs-flush_del]
root       125     2  0 18:06 ?        00:00:00 [btrfs-cache]
root       126     2  0 18:06 ?        00:00:00 [btrfs-submit]
root       127     2  0 18:06 ?        00:00:00 [btrfs-fixup]
root       128     2  0 18:06 ?        00:00:00 [btrfs-endio]
root       129     2  0 18:06 ?        00:00:00 [btrfs-endio-met]
root       130     2  0 18:06 ?        00:00:00 [btrfs-endio-met]
root       131     2  0 18:06 ?        00:00:00 [btrfs-endio-rai]
root       132     2  0 18:06 ?        00:00:00 [btrfs-endio-rep]
root       133     2  0 18:06 ?        00:00:00 [btrfs-rmw]
root       134     2  0 18:06 ?        00:00:00 [btrfs-endio-wri]
root       135     2  0 18:06 ?        00:00:00 [btrfs-freespace]
root       136     2  0 18:06 ?        00:00:00 [btrfs-delayed-m]
root       137     2  0 18:06 ?        00:00:00 [btrfs-readahead]
root       138     2  0 18:06 ?        00:00:00 [btrfs-qgroup-re]
root       139     2  0 18:06 ?        00:00:00 [btrfs-extent-re]
root       140     2  0 18:06 ?        00:00:00 [btrfs-cleaner]
root       141     2  0 18:06 ?        00:00:06 [btrfs-transacti]
root       254     2  0 18:07 ?        00:00:00 [kauditd]
root       256     1  0 18:07 ?        00:00:05 /lib/systemd/systemd-journald
root       258     1  0 18:07 ?        00:00:00 /lib/systemd/systemd-udevd
root       363     1  0 18:07 ?        00:00:04 /sbin/auditd -n
root       394     1  0 18:07 ?        00:00:00 /usr/sbin/cron -f -L 38
ctsauth    397     1  0 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/cts-auth
root       398     1  0 18:07 ?        00:00:03 /usr/bin/python /usr/local/bin/gateone
message+   402     1  0 18:07 ?        00:00:01 /usr/bin/dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd-activation
root       435     2  0 19:39 ?        00:00:00 [kworker/u5:1]
root       437     1  0 18:07 ?        00:00:00 /usr/sbin/acpid
root       438     1  0 18:07 ?        00:00:00 /lib/systemd/systemd-logind
root       441     1  0 18:07 ?        00:00:01 /usr/sbin/rsyslogd -n
root       464     1  0 18:07 tty1     00:00:00 /sbin/agetty --noclear tty1 linux
root       489     1  0 18:07 ?        00:00:00 /usr/sbin/wd_keepalive 
root       506     1  0 18:07 ?        00:00:00 /usr/sbin/mcelog --ignorenodev --daemon --foreground
root       507     1  0 18:07 ?        00:00:21 /usr/bin/python /usr/sbin/smond
root       508     1  0 18:07 ?        00:00:00 nginx: master process /usr/sbin/nginx -g daemon on; master_process on;
www-data   509   508  0 18:07 ?        00:00:00 nginx: worker process                           
root       510     1  0 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/ledmgrd
www-data   511   508  0 18:07 ?        00:00:01 nginx: worker process                           
www-data   512   508  0 18:07 ?        00:00:01 nginx: worker process                           
www-data   513   508  0 18:07 ?        00:00:01 nginx: worker process                           
root       514     1  0 18:07 ?        00:00:02 /usr/bin/python /usr/sbin/pwmd
root       515     1  0 18:07 ?        00:00:00 /usr/sbin/irqbalance --pid=/var/run/irqbalance.pid
root       554     1  0 18:07 ?        00:00:00 /usr/sbin/switchd -vx
root       575     1  0 18:07 ?        00:00:00 /usr/bin/python /usr/sbin/portwd
uuidd      703     1  0 18:07 ?        00:00:00 /usr/sbin/uuidd --socket-activation
root       755     1  1 18:07 ?        00:01:04 /usr/bin/python /usr/bin/neighmgrd
root       757     1  2 18:07 ?        00:02:15 /usr/bin/python -O /usr/sbin/netd -d
root       758     1  0 18:07 ?        00:00:00 /bin/bash /usr/lib/cumulus/sysmonitor
root       759     1  0 18:07 ?        00:00:15 /usr/bin/python /usr/sbin/netqd --daemon
frr        791     1  0 18:07 ?        00:00:08 /usr/lib/frr/zebra -M snmp -s 90000000 --daemon -A 127.0.0.1
frr        798     1  0 18:07 ?        00:00:15 /usr/lib/frr/bgpd -M snmp --daemon -A 127.0.0.1
root       806     1  0 18:07 ?        00:00:06 /usr/lib/frr/watchfrr -d -r /usr/sbin/servicebBfrrbBrestartbB%s -s /usr/sbin/servicebBfrrbBstartbB%s -k /usr/sbin/servicebBfrrbBstopbB%s -b bB -t 90 zebra bgpd
root       834     1  0 18:07 ?        00:00:00 lldpd: monitor.        
ntp        835     1  0 18:07 ?        00:00:01 /usr/sbin/ntpd -n -u ntp:ntp -g
root       836     1  0 18:07 ?        00:00:00 /usr/sbin/ptmd -l INFO
root       837     1  1 18:07 ?        00:01:03 /usr/bin/dockerd -H tcp://0.0.0.0:2375 -H unix:///var/run/docker.sock
root       838     1  0 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/netq-notifier
root       839     1  0 18:07 ?        00:00:00 /usr/sbin/dhcpd --nl -f -q
root       840     1  1 18:07 ?        00:01:36 /usr/bin/python /usr/sbin/netq-agent
root       841     1  0 18:07 ttyS0    00:00:00 /sbin/agetty --keep-baud 115200 38400 9600 ttyS0 vt102
_lldpd     857   834  0 18:07 ?        00:00:01 lldpd: 2 neighbors.    
root       887     1  0 18:07 ?        00:00:00 /usr/sbin/sshd -D
root       899   837  0 18:07 ?        00:00:42 docker-containerd --config /var/run/docker/containerd/containerd.toml
root      1128   899  0 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/4cc26bfbf1be6a4599c15f9b835a9f62a605488e0eb79e5b5ac857adbc200a80 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
root      1130   899  0 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/11b15c8fbacfa7624f9451cda0ac73e68f8beca6d145381655bcc2b94ad46693 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
root      1136   899  0 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/b2f5e1e9d1a2f5838473ec5f2396182ff65a4b74ba660b033f65e90b2c583c6a -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
root      1146   899  0 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/b6722ff84f52a4ea19d367de60a29506cf4f756eb9b40516b68c21a18e02b7fb -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
root      1152   899  0 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/d1342dce41740c07fd9ae88ce9a952edcf3cec36a3dd5c9546dad8c0e09f8141 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
root      1191     2  0 19:42 ?        00:00:00 [kworker/1:2]
root      1215  1136  0 18:08 ?        00:00:58 redis-sentinel /etc/cts/redis/snt1.conf
root      1216  1130  0 18:08 ?        00:00:00 /portainer
root      1217  1152  0 18:08 ?        00:00:40 influxd
root      1218  1128  0 18:08 ?        00:00:00 /tini -g -- /usr/sbin/netqd --daemon
systemd+  1228  1146  1 18:08 ?        00:01:23 redis-server /etc/cts/redis/redis_6379.conf
root      1321  1218  0 18:08 ?        00:00:20 /usr/bin/python /usr/sbin/netqd --daemon
root      1333     1  1 18:08 ?        00:01:16 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-gui-compose.yml up --no-color
admin     1334     1  1 18:08 ?        00:01:17 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-influxdb-compose.yml up --no-color
root      1359     1  1 18:08 ?        00:01:14 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-base-compose.yml up --no-color
root      1911   887  0 19:46 ?        00:00:00 sshd: cumulus [priv]
root      1923     2  0 19:46 ?        00:00:00 [kworker/u4:0]
root      1959   758  0 19:46 ?        00:00:00 sleep 60
cumulus   2040  1911  0 19:47 ?        00:00:00 sshd: cumulus@notty 
cumulus   2041  2040  0 19:47 ?        00:00:00 bash -c sh run.commands &> output
cumulus   2042  2041  0 19:47 ?        00:00:00 sh run.commands
root      2514   887  0 19:47 ?        00:00:00 sshd: cumulus [priv]
sshd      2515  2514  0 19:47 ?        00:00:00 sshd: cumulus [net] 
root      2646  2042  0 19:47 ?        00:00:00 sudo nohup ps -ef
root      2651  2646  0 19:47 ?        00:00:00 ps -ef
root     17616     2  0 18:45 ?        00:00:01 [kworker/u4:1]
root     25029   398  0 19:09 pts/1    00:00:00 /bin/sh -c dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S '/tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET%' --sshfp -a '-oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"'; sleep .1
root     25030 25029  0 19:09 pts/1    00:00:00 dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET% --sshfp -a -oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"
root     25031 25030  0 19:09 ?        00:00:00 dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET% --sshfp -a -oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"
root     25032 25031  0 19:09 pts/2    00:00:00 sh -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22 && rm -f /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22
root     25034 25032  0 19:09 pts/2    00:00:00 /bin/sh /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22
root     25035 25034  0 19:09 pts/2    00:00:00 ssh -M -S/tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/JTw8Am_C -x -F/opt/gateone/users/ANONYMOUS/.ssh/config -oNoHostAuthenticationForLocalhost=yes -oVerifyHostKeyDNS=yes -oPreferredAuthentications=keyboard-interactive,password -oIdentitiesOnly=yes -oSendEnv=GO_TERM GO_LOCATION GO_SESSION -p 22 -l cumulus -oUserKnownHostsFile="/opt/gateone/users/ANONYMOUS/.ssh/known_hosts" localhost
root     25036   887  0 19:09 ?        00:00:00 sshd: cumulus [priv]
cumulus  25079 25036  0 19:09 ?        00:00:00 sshd: cumulus@pts/3 
cumulus  25080 25079  0 19:09 pts/3    00:00:00 -bash
root     26130     2  0 19:13 ?        00:00:00 [kworker/u4:2]
root     27520     2  0 19:17 ?        00:00:00 [kworker/1:1]
root     28137     2  0 19:19 ?        00:00:00 [kworker/u4:3]
root     28598     2  0 19:21 ?        00:00:00 [kworker/u5:2]
root     30600     2  0 19:27 ?        00:00:00 [kworker/1:0]
root     31693     2  0 19:32 ?        00:00:00 [kworker/0:0]
root     31742     2  0 19:33 ?        00:00:00 [kworker/u5:0]
root     32620     2  0 19:37 ?        00:00:00 [kworker/0:1]

```
```


Usage:
 ps [options]

 Try 'ps --help <simple|list|output|threads|misc|all>'
  or 'ps --help <s|l|o|t|m|a>'
 for additional help text.

For more details see ps(1).

UID        PID  PPID  C STIME TTY          TIME CMD
root         1     0  0 18:06 ?        00:00:32 /sbin/init
root         2     0  0 18:06 ?        00:00:00 [kthreadd]
root         3     2  0 18:06 ?        00:00:40 [ksoftirqd/0]
root         5     2  0 18:06 ?        00:00:00 [kworker/0:0H]
root         7     2  0 18:06 ?        00:00:05 [rcu_sched]
root         8     2  0 18:06 ?        00:00:00 [rcu_bh]
root         9     2  0 18:06 ?        00:00:01 [migration/0]
root        10     2  0 18:06 ?        00:00:00 [watchdog/0]
root        11     2  0 18:06 ?        00:00:00 [watchdog/1]
root        12     2  0 18:06 ?        00:00:01 [migration/1]
root        13     2  0 18:06 ?        00:00:41 [ksoftirqd/1]
root        15     2  0 18:06 ?        00:00:00 [kworker/1:0H]
root        16     2  0 18:06 ?        00:00:00 [khelper]
root        17     2  0 18:06 ?        00:00:00 [kdevtmpfs]
root        18     2  0 18:06 ?        00:00:00 [netns]
root        19     2  0 18:06 ?        00:00:00 [perf]
root        20     2  0 18:06 ?        00:00:00 [khungtaskd]
root        21     2  0 18:06 ?        00:00:00 [writeback]
root        23     2  0 18:06 ?        00:00:00 [ksmd]
root        24     2  0 18:06 ?        00:00:00 [khugepaged]
root        25     2  0 18:06 ?        00:00:00 [crypto]
root        26     2  0 18:06 ?        00:00:00 [kintegrityd]
root        27     2  0 18:06 ?        00:00:00 [bioset]
root        28     2  0 18:06 ?        00:00:00 [kblockd]
root        29     2  0 18:06 ?        00:00:00 [ata_sff]
root        30     2  0 18:06 ?        00:00:00 [edac-poller]
root        32     2  0 18:06 ?        00:00:00 [rpciod]
root        33     2  0 18:06 ?        00:00:00 [kswapd0]
root        34     2  0 18:06 ?        00:00:00 [fsnotify_mark]
root        35     2  0 18:06 ?        00:00:00 [nfsiod]
root        44     2  0 18:06 ?        00:00:00 [kthrotld]
root        45     2  0 18:06 ?        00:00:00 [scsi_eh_0]
root        46     2  0 18:06 ?        00:00:00 [scsi_tmf_0]
root        47     2  0 18:06 ?        00:00:00 [scsi_eh_1]
root        48     2  0 18:06 ?        00:00:00 [scsi_tmf_1]
root        51     2  0 18:06 ?        00:00:00 [ipv6_addrconf]
root        52     2  0 18:06 ?        00:00:00 [deferwq]
root        89     2  0 18:06 ?        00:00:01 [kworker/1:1H]
root        91     2  0 18:06 ?        00:00:01 [kworker/0:1H]
root       103     2  0 18:06 ?        00:00:00 [bioset]
root       120     2  0 18:06 ?        00:00:00 [btrfs-worker]
root       122     2  0 18:06 ?        00:00:00 [btrfs-worker-hi]
root       123     2  0 18:06 ?        00:00:00 [btrfs-delalloc]
root       124     2  0 18:06 ?        00:00:00 [btrfs-flush_del]
root       125     2  0 18:06 ?        00:00:00 [btrfs-cache]
root       126     2  0 18:06 ?        00:00:00 [btrfs-submit]
root       127     2  0 18:06 ?        00:00:00 [btrfs-fixup]
root       128     2  0 18:06 ?        00:00:00 [btrfs-endio]
root       129     2  0 18:06 ?        00:00:00 [btrfs-endio-met]
root       130     2  0 18:06 ?        00:00:00 [btrfs-endio-met]
root       131     2  0 18:06 ?        00:00:00 [btrfs-endio-rai]
root       132     2  0 18:06 ?        00:00:00 [btrfs-endio-rep]
root       133     2  0 18:06 ?        00:00:00 [btrfs-rmw]
root       134     2  0 18:06 ?        00:00:00 [btrfs-endio-wri]
root       135     2  0 18:06 ?        00:00:00 [btrfs-freespace]
root       136     2  0 18:06 ?        00:00:00 [btrfs-delayed-m]
root       137     2  0 18:06 ?        00:00:00 [btrfs-readahead]
root       138     2  0 18:06 ?        00:00:00 [btrfs-qgroup-re]
root       139     2  0 18:06 ?        00:00:00 [btrfs-extent-re]
root       140     2  0 18:06 ?        00:00:00 [btrfs-cleaner]
root       141     2  0 18:06 ?        00:00:06 [btrfs-transacti]
root       254     2  0 18:07 ?        00:00:00 [kauditd]
root       256     1  0 18:07 ?        00:00:05 /lib/systemd/systemd-journald
root       258     1  0 18:07 ?        00:00:00 /lib/systemd/systemd-udevd
root       363     1  0 18:07 ?        00:00:04 /sbin/auditd -n
root       394     1  0 18:07 ?        00:00:00 /usr/sbin/cron -f -L 38
ctsauth    397     1  0 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/cts-auth
root       398     1  0 18:07 ?        00:00:03 /usr/bin/python /usr/local/bin/gateone
message+   402     1  0 18:07 ?        00:00:01 /usr/bin/dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd-activation
root       435     2  0 19:39 ?        00:00:00 [kworker/u5:1]
root       437     1  0 18:07 ?        00:00:00 /usr/sbin/acpid
root       438     1  0 18:07 ?        00:00:00 /lib/systemd/systemd-logind
root       441     1  0 18:07 ?        00:00:01 /usr/sbin/rsyslogd -n
root       464     1  0 18:07 tty1     00:00:00 /sbin/agetty --noclear tty1 linux
root       489     1  0 18:07 ?        00:00:00 /usr/sbin/wd_keepalive 
root       506     1  0 18:07 ?        00:00:00 /usr/sbin/mcelog --ignorenodev --daemon --foreground
root       507     1  0 18:07 ?        00:00:21 /usr/bin/python /usr/sbin/smond
root       508     1  0 18:07 ?        00:00:00 nginx: master process /usr/sbin/nginx -g daemon on; master_process on;
www-data   509   508  0 18:07 ?        00:00:00 nginx: worker process                           
root       510     1  0 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/ledmgrd
www-data   511   508  0 18:07 ?        00:00:01 nginx: worker process                           
www-data   512   508  0 18:07 ?        00:00:01 nginx: worker process                           
www-data   513   508  0 18:07 ?        00:00:01 nginx: worker process                           
root       514     1  0 18:07 ?        00:00:02 /usr/bin/python /usr/sbin/pwmd
root       515     1  0 18:07 ?        00:00:00 /usr/sbin/irqbalance --pid=/var/run/irqbalance.pid
root       554     1  0 18:07 ?        00:00:00 /usr/sbin/switchd -vx
root       575     1  0 18:07 ?        00:00:00 /usr/bin/python /usr/sbin/portwd
uuidd      703     1  0 18:07 ?        00:00:00 /usr/sbin/uuidd --socket-activation
root       755     1  1 18:07 ?        00:01:04 /usr/bin/python /usr/bin/neighmgrd
root       757     1  2 18:07 ?        00:02:15 /usr/bin/python -O /usr/sbin/netd -d
root       758     1  0 18:07 ?        00:00:00 /bin/bash /usr/lib/cumulus/sysmonitor
root       759     1  0 18:07 ?        00:00:15 /usr/bin/python /usr/sbin/netqd --daemon
frr        791     1  0 18:07 ?        00:00:08 /usr/lib/frr/zebra -M snmp -s 90000000 --daemon -A 127.0.0.1
frr        798     1  0 18:07 ?        00:00:15 /usr/lib/frr/bgpd -M snmp --daemon -A 127.0.0.1
root       806     1  0 18:07 ?        00:00:06 /usr/lib/frr/watchfrr -d -r /usr/sbin/servicebBfrrbBrestartbB%s -s /usr/sbin/servicebBfrrbBstartbB%s -k /usr/sbin/servicebBfrrbBstopbB%s -b bB -t 90 zebra bgpd
root       834     1  0 18:07 ?        00:00:00 lldpd: monitor.        
ntp        835     1  0 18:07 ?        00:00:01 /usr/sbin/ntpd -n -u ntp:ntp -g
root       836     1  0 18:07 ?        00:00:00 /usr/sbin/ptmd -l INFO
root       837     1  1 18:07 ?        00:01:03 /usr/bin/dockerd -H tcp://0.0.0.0:2375 -H unix:///var/run/docker.sock
root       838     1  0 18:07 ?        00:00:01 /usr/bin/python /usr/sbin/netq-notifier
root       839     1  0 18:07 ?        00:00:00 /usr/sbin/dhcpd --nl -f -q
root       840     1  1 18:07 ?        00:01:36 /usr/bin/python /usr/sbin/netq-agent
root       841     1  0 18:07 ttyS0    00:00:00 /sbin/agetty --keep-baud 115200 38400 9600 ttyS0 vt102
_lldpd     857   834  0 18:07 ?        00:00:01 lldpd: 2 neighbors.    
root       887     1  0 18:07 ?        00:00:00 /usr/sbin/sshd -D
root       899   837  0 18:07 ?        00:00:42 docker-containerd --config /var/run/docker/containerd/containerd.toml
root      1128   899  0 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/4cc26bfbf1be6a4599c15f9b835a9f62a605488e0eb79e5b5ac857adbc200a80 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
root      1130   899  0 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/11b15c8fbacfa7624f9451cda0ac73e68f8beca6d145381655bcc2b94ad46693 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
root      1136   899  0 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/b2f5e1e9d1a2f5838473ec5f2396182ff65a4b74ba660b033f65e90b2c583c6a -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
root      1146   899  0 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/b6722ff84f52a4ea19d367de60a29506cf4f756eb9b40516b68c21a18e02b7fb -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
root      1152   899  0 18:08 ?        00:00:00 docker-containerd-shim -namespace moby -workdir /var/lib/docker/containerd/daemon/io.containerd.runtime.v1.linux/moby/d1342dce41740c07fd9ae88ce9a952edcf3cec36a3dd5c9546dad8c0e09f8141 -address /var/run/docker/containerd/docker-containerd.sock -containerd-binary /usr/bin/docker-containerd -runtime-root /var/run/docker/runtime-runc
root      1191     2  0 19:42 ?        00:00:00 [kworker/1:2]
root      1215  1136  0 18:08 ?        00:00:58 redis-sentinel /etc/cts/redis/snt1.conf
root      1216  1130  0 18:08 ?        00:00:00 /portainer
root      1217  1152  0 18:08 ?        00:00:40 influxd
root      1218  1128  0 18:08 ?        00:00:00 /tini -g -- /usr/sbin/netqd --daemon
systemd+  1228  1146  1 18:08 ?        00:01:23 redis-server /etc/cts/redis/redis_6379.conf
root      1321  1218  0 18:08 ?        00:00:20 /usr/bin/python /usr/sbin/netqd --daemon
root      1333     1  1 18:08 ?        00:01:16 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-gui-compose.yml up --no-color
admin     1334     1  1 18:08 ?        00:01:17 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-influxdb-compose.yml up --no-color
root      1359     1  1 18:08 ?        00:01:14 /usr/bin/python2 /usr/local/bin/docker-compose -p netq -f /etc/cts/docker/netq-base-compose.yml up --no-color
root      1911   887  0 19:46 ?        00:00:00 sshd: cumulus [priv]
root      1923     2  0 19:46 ?        00:00:00 [kworker/u4:0]
root      1959   758  0 19:46 ?        00:00:00 sleep 60
cumulus   2040  1911  0 19:47 ?        00:00:00 sshd: cumulus@notty 
cumulus   2041  2040  0 19:47 ?        00:00:00 bash -c sh run.commands &> output
cumulus   2042  2041  0 19:47 ?        00:00:00 sh run.commands
root      2514   887  0 19:47 ?        00:00:00 sshd: cumulus [priv]
sshd      2515  2514  0 19:47 ?        00:00:00 sshd: cumulus [net] 
root      2646  2042  0 19:47 ?        00:00:00 sudo nohup ps -ef
root      2651  2646  0 19:47 ?        00:00:00 ps -ef
root     17616     2  0 18:45 ?        00:00:01 [kworker/u4:1]
root     25029   398  0 19:09 pts/1    00:00:00 /bin/sh -c dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S '/tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET%' --sshfp -a '-oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"'; sleep .1
root     25030 25029  0 19:09 pts/1    00:00:00 dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET% --sshfp -a -oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"
root     25031 25030  0 19:09 ?        00:00:00 dtach -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/dtach_default_1 -E -z -r none /usr/local/lib/python2.7/dist-packages/gateone-1.2.0-py2.7.egg/gateone/applications/terminal/plugins/ssh/scripts/ssh_connect.py -S /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/%SHORT_SOCKET% --sshfp -a -oUserKnownHostsFile=\"/opt/gateone/users/ANONYMOUS/.ssh/known_hosts\"
root     25032 25031  0 19:09 pts/2    00:00:00 sh -c /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22 && rm -f /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22
root     25034 25032  0 19:09 pts/2    00:00:00 /bin/sh /tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/ssh:default:1:cumulus@localhost:22
root     25035 25034  0 19:09 pts/2    00:00:00 ssh -M -S/tmp/gateone/Y2ZkNzdmYTk3NTZlNGRiOGE1MTVkMDRkOTVlYjNmZWQyN/JTw8Am_C -x -F/opt/gateone/users/ANONYMOUS/.ssh/config -oNoHostAuthenticationForLocalhost=yes -oVerifyHostKeyDNS=yes -oPreferredAuthentications=keyboard-interactive,password -oIdentitiesOnly=yes -oSendEnv=GO_TERM GO_LOCATION GO_SESSION -p 22 -l cumulus -oUserKnownHostsFile="/opt/gateone/users/ANONYMOUS/.ssh/known_hosts" localhost
root     25036   887  0 19:09 ?        00:00:00 sshd: cumulus [priv]
cumulus  25079 25036  0 19:09 ?        00:00:00 sshd: cumulus@pts/3 
cumulus  25080 25079  0 19:09 pts/3    00:00:00 -bash
root     26130     2  0 19:13 ?        00:00:00 [kworker/u4:2]
root     27520     2  0 19:17 ?        00:00:00 [kworker/1:1]
root     28137     2  0 19:19 ?        00:00:00 [kworker/u4:3]
root     28598     2  0 19:21 ?        00:00:00 [kworker/u5:2]
root     30600     2  0 19:27 ?        00:00:00 [kworker/1:0]
root     31693     2  0 19:32 ?        00:00:00 [kworker/0:0]
root     31742     2  0 19:33 ?        00:00:00 [kworker/u5:0]
root     32620     2  0 19:37 ?        00:00:00 [kworker/0:1]

```
## sudo lsof -i
```

COMMAND     PID             USER   FD   TYPE DEVICE SIZE/OFF NODE NAME
gateone     398             root    8u  IPv6  14616      0t0  TCP *:1337 (LISTEN)
gateone     398             root    9u  IPv4  14617      0t0  TCP *:1337 (LISTEN)
gateone     398             root   14u  IPv4 169533      0t0  TCP 10.255.0.1:1337->172-5-126-131.lightspeed.sntcca.sbcglobal.net:60592 (ESTABLISHED)
nginx       508             root    8u  IPv4  12212      0t0  TCP *:9999 (LISTEN)
nginx       508             root    9u  IPv4  12213      0t0  TCP *:5000 (LISTEN)
nginx       508             root   10u  IPv6  12214      0t0  TCP *:http-alt (LISTEN)
nginx       509         www-data    8u  IPv4  12212      0t0  TCP *:9999 (LISTEN)
nginx       509         www-data    9u  IPv4  12213      0t0  TCP *:5000 (LISTEN)
nginx       509         www-data   10u  IPv6  12214      0t0  TCP *:http-alt (LISTEN)
nginx       511         www-data    8u  IPv4  12212      0t0  TCP *:9999 (LISTEN)
nginx       511         www-data    9u  IPv4  12213      0t0  TCP *:5000 (LISTEN)
nginx       511         www-data   10u  IPv6  12214      0t0  TCP *:http-alt (LISTEN)
nginx       512         www-data    8u  IPv4  12212      0t0  TCP *:9999 (LISTEN)
nginx       512         www-data    9u  IPv4  12213      0t0  TCP *:5000 (LISTEN)
nginx       512         www-data   10u  IPv6  12214      0t0  TCP *:http-alt (LISTEN)
nginx       513         www-data    8u  IPv4  12212      0t0  TCP *:9999 (LISTEN)
nginx       513         www-data    9u  IPv4  12213      0t0  TCP *:5000 (LISTEN)
nginx       513         www-data   10u  IPv6  12214      0t0  TCP *:http-alt (LISTEN)
zebra       791              frr   17u  IPv4  14962      0t0  TCP localhost:zebra (LISTEN)
bgpd        798              frr   16u  IPv4  14972      0t0  TCP localhost:bgpd (LISTEN)
bgpd        798              frr   21u  IPv6  16420      0t0  TCP [fe80::4638:39ff:fe00:103]:60999->[fe80::4638:39ff:fe00:307]:bgp (ESTABLISHED)
bgpd        798              frr   22u  IPv4  15059      0t0  TCP *:bgp (LISTEN)
bgpd        798              frr   23u  IPv6  15060      0t0  TCP *:bgp (LISTEN)
bgpd        798              frr   24u  IPv6  16529      0t0  TCP [fe80::4638:39ff:fe00:102]:55410->[fe80::4638:39ff:fe00:207]:bgp (ESTABLISHED)
ntpd        835              ntp   16u  IPv4  15184      0t0  UDP *:ntp 
ntpd        835              ntp   17u  IPv6  15185      0t0  UDP *:ntp 
ntpd        835              ntp   18u  IPv4  15190      0t0  UDP localhost:ntp 
ntpd        835              ntp   19u  IPv4  15191      0t0  UDP 10.255.0.1:ntp 
ntpd        835              ntp   20u  IPv6  15192      0t0  UDP localhost:ntp 
ntpd        835              ntp   21u  IPv6  15193      0t0  UDP [fe80::4638:39ff:fe00:100]:ntp 
ptmd        836             root    8u  IPv4  15321      0t0  UDP *:3784 
ptmd        836             root    9u  IPv4  15322      0t0  UDP *:4784 
ptmd        836             root   10u  IPv6  15323      0t0  UDP *:3784 
ptmd        836             root   11u  IPv6  15324      0t0  UDP *:4784 
ptmd        836             root   13u  IPv4  15326      0t0  UDP *:3785 
dockerd     837             root    6u  IPv6  16501      0t0  TCP *:2375 (LISTEN)
dockerd     837             root   45u  IPv6  19001      0t0  TCP localhost:2375->localhost:53438 (ESTABLISHED)
dockerd     837             root   46u  IPv6  19004      0t0  TCP localhost:2375->localhost:53439 (ESTABLISHED)
dockerd     837             root   47u  IPv6  19007      0t0  TCP localhost:2375->localhost:53440 (ESTABLISHED)
dockerd     837             root   48u  IPv6  20014      0t0  TCP localhost:2375->localhost:53441 (ESTABLISHED)
dockerd     837             root   49u  IPv6  20017      0t0  TCP localhost:2375->localhost:53442 (ESTABLISHED)
dockerd     837             root   50u  IPv6  19048      0t0  TCP localhost:2375->localhost:53443 (ESTABLISHED)
dockerd     837             root   51u  IPv6  19050      0t0  TCP localhost:2375->localhost:53444 (ESTABLISHED)
dockerd     837             root   52u  IPv6  19053      0t0  TCP localhost:2375->localhost:53445 (ESTABLISHED)
dhcpd       839             root    8u  IPv4  16373      0t0  UDP *:bootps 
dhcpd       839             root   20u  IPv4  16394      0t0  UDP *:13019 
dhcpd       839             root   21u  IPv6  16395      0t0  UDP *:6806 
netq-agen   840             root    5u  IPv4  20163      0t0  TCP oob-mgmt-server:51045->oob-mgmt-server:6379 (ESTABLISHED)
sshd        887             root    3u  IPv4  17581      0t0  TCP *:ssh (LISTEN)
sshd        887             root    4u  IPv6  16488      0t0  TCP *:ssh (LISTEN)
redis-sen  1215             root    4u  IPv6  18560      0t0  TCP *:26379 (LISTEN)
redis-sen  1215             root    5u  IPv4  18561      0t0  TCP *:26379 (LISTEN)
portainer  1216             root    4u  IPv6  19493      0t0  TCP *:9000 (LISTEN)
influxd    1217             root    3u  IPv4  19658      0t0  TCP localhost:omniorb (LISTEN)
influxd    1217             root    8u  IPv6  20021      0t0  TCP *:8086 (LISTEN)
redis-ser  1228 systemd-timesync    4u  IPv6  18565      0t0  TCP *:6379 (LISTEN)
redis-ser  1228 systemd-timesync    5u  IPv4  18566      0t0  TCP *:6379 (LISTEN)
redis-ser  1228 systemd-timesync    7u  IPv4 141803      0t0  TCP oob-mgmt-server:6379->leaf03:47542 (ESTABLISHED)
redis-ser  1228 systemd-timesync   10u  IPv4  19232      0t0  TCP oob-mgmt-server:6379->leaf02:48898 (ESTABLISHED)
redis-ser  1228 systemd-timesync   11u  IPv4  19234      0t0  TCP oob-mgmt-server:6379->spine01:59346 (ESTABLISHED)
redis-ser  1228 systemd-timesync   12u  IPv4  19228      0t0  TCP oob-mgmt-server:6379->oob-mgmt-server:51045 (ESTABLISHED)
redis-ser  1228 systemd-timesync   13u  IPv4  20169      0t0  TCP oob-mgmt-server:6379->server03:43482 (ESTABLISHED)
redis-ser  1228 systemd-timesync   15u  IPv4  19370      0t0  TCP oob-mgmt-server:6379->server01:35238 (ESTABLISHED)
redis-ser  1228 systemd-timesync   16u  IPv4  20193      0t0  TCP oob-mgmt-server:6379->server02:59278 (ESTABLISHED)
redis-ser  1228 systemd-timesync   17u  IPv4 105901      0t0  TCP oob-mgmt-server:6379->leaf04:46062 (ESTABLISHED)
redis-ser  1228 systemd-timesync   18u  IPv4 161284      0t0  TCP oob-mgmt-server:6379->server04:56912 (ESTABLISHED)
redis-ser  1228 systemd-timesync   19u  IPv4  20221      0t0  TCP oob-mgmt-server:6379->spine02:56172 (ESTABLISHED)
redis-ser  1228 systemd-timesync   20u  IPv4  20606      0t0  TCP oob-mgmt-server:6379->leaf01:34884 (ESTABLISHED)
docker-co  1333             root    3u  IPv4  19003      0t0  TCP localhost:53439->localhost:2375 (ESTABLISHED)
docker-co  1333             root    4u  IPv4  19047      0t0  TCP localhost:53441->localhost:2375 (ESTABLISHED)
docker-co  1334            admin    3u  IPv4  19006      0t0  TCP localhost:53440->localhost:2375 (ESTABLISHED)
docker-co  1334            admin    4u  IPv4  20016      0t0  TCP localhost:53442->localhost:2375 (ESTABLISHED)
docker-co  1359             root    3u  IPv4  20009      0t0  TCP localhost:53438->localhost:2375 (ESTABLISHED)
docker-co  1359             root    4u  IPv4  20019      0t0  TCP localhost:53443->localhost:2375 (ESTABLISHED)
docker-co  1359             root    5u  IPv4  20020      0t0  TCP localhost:53444->localhost:2375 (ESTABLISHED)
docker-co  1359             root    6u  IPv4  19052      0t0  TCP localhost:53445->localhost:2375 (ESTABLISHED)
sshd       1911             root    3u  IPv4 175555      0t0  TCP 10.255.0.1:ssh->172-5-126-131.lightspeed.sntcca.sbcglobal.net:60617 (ESTABLISHED)
sshd       2040          cumulus    3u  IPv4 175555      0t0  TCP 10.255.0.1:ssh->172-5-126-131.lightspeed.sntcca.sbcglobal.net:60617 (ESTABLISHED)
sshd       2514             root    3u  IPv4 179212      0t0  TCP 10.255.0.1:ssh->172-5-126-131.lightspeed.sntcca.sbcglobal.net:60630 (ESTABLISHED)
sshd       2515             sshd    3u  IPv4 179212      0t0  TCP 10.255.0.1:ssh->172-5-126-131.lightspeed.sntcca.sbcglobal.net:60630 (ESTABLISHED)
ssh       25035             root    3u  IPv6 126602      0t0  TCP localhost:35072->localhost:ssh (ESTABLISHED)
sshd      25036             root    3u  IPv6 126603      0t0  TCP localhost:ssh->localhost:35072 (ESTABLISHED)
sshd      25079          cumulus    3u  IPv6 126603      0t0  TCP localhost:ssh->localhost:35072 (ESTABLISHED)

```
```

lsof: illegal option character: -
lsof: -e not followed by a file system path: "lp"
lsof 4.86
 latest revision: ftp://lsof.itap.purdue.edu/pub/tools/unix/lsof/
 latest FAQ: ftp://lsof.itap.purdue.edu/pub/tools/unix/lsof/FAQ
 latest man page: ftp://lsof.itap.purdue.edu/pub/tools/unix/lsof/lsof_man
 usage: [-?abhKlnNoOPRtUvVX] [+|-c c] [+|-d s] [+D D] [+|-f[gG]] [+|-e s]
 [-F [f]] [-g [s]] [-i [i]] [+|-L [l]] [+m [m]] [+|-M] [-o [o]] [-p s]
[+|-r [t]] [-s [p:s]] [-S [t]] [-T [t]] [-u s] [+|-w] [-x [fl]] [--] [names]
Defaults in parentheses; comma-separated set (s) items; dash-separated ranges.
  -?|-h list help          -a AND selections (OR)     -b avoid kernel blocks
  -c c  cmd c ^c /c/[bix]  +c w  COMMAND width (9)    +d s  dir s files
  -d s  select by FD set   +D D  dir D tree *SLOW?*   +|-e s  exempt s *RISKY*
  -i select IPv[46] files  -K list tasKs              -l list UID numbers
  -n no host names         -N select NFS files        -o list file offset
  -O no overhead *RISKY*   -P no port names           -R list paRent PID
  -s list file size        -t terse listing           -T disable TCP/TPI info
  -U select Unix socket    -v list version info       -V verbose search
  +|-w  Warnings (+)       -X skip TCP&UDP* files     -- end option scan
  +f|-f  +filesystem or -file names     +|-f[gG] flaGs 
  -F [f] select fields; -F? for help  
  +|-L [l] list (+) suppress (-) link counts < l (0 = all; default = 0)
                                        +m [m] use|create mount supplement
  +|-M   portMap registration (-)       -o o   o 0t offset digits (8)
  -p s   exclude(^)|select PIDs         -S [t] t second stat timeout (15)
  -T qs TCP/TPI Q,St (s) info
  -g [s] exclude(^)|select and print process group IDs
  -i i   select by IPv[46] address: [46][proto][@host|addr][:svc_list|port_list]
  +|-r [t[m<fmt>]] repeat every t seconds (15);  + until no files, - forever.
       An optional suffix to t is m<fmt>; m must separate t from <fmt> and
      <fmt> is an strftime(3) format for the marker line.
  -s p:s  exclude(^)|select protocol (p = TCP|UDP) states by name(s).
  -u s   exclude(^)|select login|UID set s
  -x [fl] cross over +d|+D File systems or symbolic Links
  names  select named files or files on named file systems
Anyone can list all files; /dev warnings disabled; kernel ID check disabled.

COMMAND     PID             USER   FD   TYPE DEVICE SIZE/OFF NODE NAME
gateone     398             root    8u  IPv6  14616      0t0  TCP *:1337 (LISTEN)
gateone     398             root    9u  IPv4  14617      0t0  TCP *:1337 (LISTEN)
gateone     398             root   14u  IPv4 169533      0t0  TCP 10.255.0.1:1337->172-5-126-131.lightspeed.sntcca.sbcglobal.net:60592 (ESTABLISHED)
nginx       508             root    8u  IPv4  12212      0t0  TCP *:9999 (LISTEN)
nginx       508             root    9u  IPv4  12213      0t0  TCP *:5000 (LISTEN)
nginx       508             root   10u  IPv6  12214      0t0  TCP *:http-alt (LISTEN)
nginx       509         www-data    8u  IPv4  12212      0t0  TCP *:9999 (LISTEN)
nginx       509         www-data    9u  IPv4  12213      0t0  TCP *:5000 (LISTEN)
nginx       509         www-data   10u  IPv6  12214      0t0  TCP *:http-alt (LISTEN)
nginx       511         www-data    8u  IPv4  12212      0t0  TCP *:9999 (LISTEN)
nginx       511         www-data    9u  IPv4  12213      0t0  TCP *:5000 (LISTEN)
nginx       511         www-data   10u  IPv6  12214      0t0  TCP *:http-alt (LISTEN)
nginx       512         www-data    8u  IPv4  12212      0t0  TCP *:9999 (LISTEN)
nginx       512         www-data    9u  IPv4  12213      0t0  TCP *:5000 (LISTEN)
nginx       512         www-data   10u  IPv6  12214      0t0  TCP *:http-alt (LISTEN)
nginx       513         www-data    8u  IPv4  12212      0t0  TCP *:9999 (LISTEN)
nginx       513         www-data    9u  IPv4  12213      0t0  TCP *:5000 (LISTEN)
nginx       513         www-data   10u  IPv6  12214      0t0  TCP *:http-alt (LISTEN)
zebra       791              frr   17u  IPv4  14962      0t0  TCP localhost:zebra (LISTEN)
bgpd        798              frr   16u  IPv4  14972      0t0  TCP localhost:bgpd (LISTEN)
bgpd        798              frr   21u  IPv6  16420      0t0  TCP [fe80::4638:39ff:fe00:103]:60999->[fe80::4638:39ff:fe00:307]:bgp (ESTABLISHED)
bgpd        798              frr   22u  IPv4  15059      0t0  TCP *:bgp (LISTEN)
bgpd        798              frr   23u  IPv6  15060      0t0  TCP *:bgp (LISTEN)
bgpd        798              frr   24u  IPv6  16529      0t0  TCP [fe80::4638:39ff:fe00:102]:55410->[fe80::4638:39ff:fe00:207]:bgp (ESTABLISHED)
ntpd        835              ntp   16u  IPv4  15184      0t0  UDP *:ntp 
ntpd        835              ntp   17u  IPv6  15185      0t0  UDP *:ntp 
ntpd        835              ntp   18u  IPv4  15190      0t0  UDP localhost:ntp 
ntpd        835              ntp   19u  IPv4  15191      0t0  UDP 10.255.0.1:ntp 
ntpd        835              ntp   20u  IPv6  15192      0t0  UDP localhost:ntp 
ntpd        835              ntp   21u  IPv6  15193      0t0  UDP [fe80::4638:39ff:fe00:100]:ntp 
ptmd        836             root    8u  IPv4  15321      0t0  UDP *:3784 
ptmd        836             root    9u  IPv4  15322      0t0  UDP *:4784 
ptmd        836             root   10u  IPv6  15323      0t0  UDP *:3784 
ptmd        836             root   11u  IPv6  15324      0t0  UDP *:4784 
ptmd        836             root   13u  IPv4  15326      0t0  UDP *:3785 
dockerd     837             root    6u  IPv6  16501      0t0  TCP *:2375 (LISTEN)
dockerd     837             root   45u  IPv6  19001      0t0  TCP localhost:2375->localhost:53438 (ESTABLISHED)
dockerd     837             root   46u  IPv6  19004      0t0  TCP localhost:2375->localhost:53439 (ESTABLISHED)
dockerd     837             root   47u  IPv6  19007      0t0  TCP localhost:2375->localhost:53440 (ESTABLISHED)
dockerd     837             root   48u  IPv6  20014      0t0  TCP localhost:2375->localhost:53441 (ESTABLISHED)
dockerd     837             root   49u  IPv6  20017      0t0  TCP localhost:2375->localhost:53442 (ESTABLISHED)
dockerd     837             root   50u  IPv6  19048      0t0  TCP localhost:2375->localhost:53443 (ESTABLISHED)
dockerd     837             root   51u  IPv6  19050      0t0  TCP localhost:2375->localhost:53444 (ESTABLISHED)
dockerd     837             root   52u  IPv6  19053      0t0  TCP localhost:2375->localhost:53445 (ESTABLISHED)
dhcpd       839             root    8u  IPv4  16373      0t0  UDP *:bootps 
dhcpd       839             root   20u  IPv4  16394      0t0  UDP *:13019 
dhcpd       839             root   21u  IPv6  16395      0t0  UDP *:6806 
netq-agen   840             root    5u  IPv4  20163      0t0  TCP oob-mgmt-server:51045->oob-mgmt-server:6379 (ESTABLISHED)
sshd        887             root    3u  IPv4  17581      0t0  TCP *:ssh (LISTEN)
sshd        887             root    4u  IPv6  16488      0t0  TCP *:ssh (LISTEN)
redis-sen  1215             root    4u  IPv6  18560      0t0  TCP *:26379 (LISTEN)
redis-sen  1215             root    5u  IPv4  18561      0t0  TCP *:26379 (LISTEN)
portainer  1216             root    4u  IPv6  19493      0t0  TCP *:9000 (LISTEN)
influxd    1217             root    3u  IPv4  19658      0t0  TCP localhost:omniorb (LISTEN)
influxd    1217             root    8u  IPv6  20021      0t0  TCP *:8086 (LISTEN)
redis-ser  1228 systemd-timesync    4u  IPv6  18565      0t0  TCP *:6379 (LISTEN)
redis-ser  1228 systemd-timesync    5u  IPv4  18566      0t0  TCP *:6379 (LISTEN)
redis-ser  1228 systemd-timesync    7u  IPv4 141803      0t0  TCP oob-mgmt-server:6379->leaf03:47542 (ESTABLISHED)
redis-ser  1228 systemd-timesync   10u  IPv4  19232      0t0  TCP oob-mgmt-server:6379->leaf02:48898 (ESTABLISHED)
redis-ser  1228 systemd-timesync   11u  IPv4  19234      0t0  TCP oob-mgmt-server:6379->spine01:59346 (ESTABLISHED)
redis-ser  1228 systemd-timesync   12u  IPv4  19228      0t0  TCP oob-mgmt-server:6379->oob-mgmt-server:51045 (ESTABLISHED)
redis-ser  1228 systemd-timesync   13u  IPv4  20169      0t0  TCP oob-mgmt-server:6379->server03:43482 (ESTABLISHED)
redis-ser  1228 systemd-timesync   15u  IPv4  19370      0t0  TCP oob-mgmt-server:6379->server01:35238 (ESTABLISHED)
redis-ser  1228 systemd-timesync   16u  IPv4  20193      0t0  TCP oob-mgmt-server:6379->server02:59278 (ESTABLISHED)
redis-ser  1228 systemd-timesync   17u  IPv4 105901      0t0  TCP oob-mgmt-server:6379->leaf04:46062 (ESTABLISHED)
redis-ser  1228 systemd-timesync   18u  IPv4 161284      0t0  TCP oob-mgmt-server:6379->server04:56912 (ESTABLISHED)
redis-ser  1228 systemd-timesync   19u  IPv4  20221      0t0  TCP oob-mgmt-server:6379->spine02:56172 (ESTABLISHED)
redis-ser  1228 systemd-timesync   20u  IPv4  20606      0t0  TCP oob-mgmt-server:6379->leaf01:34884 (ESTABLISHED)
docker-co  1333             root    3u  IPv4  19003      0t0  TCP localhost:53439->localhost:2375 (ESTABLISHED)
docker-co  1333             root    4u  IPv4  19047      0t0  TCP localhost:53441->localhost:2375 (ESTABLISHED)
docker-co  1334            admin    3u  IPv4  19006      0t0  TCP localhost:53440->localhost:2375 (ESTABLISHED)
docker-co  1334            admin    4u  IPv4  20016      0t0  TCP localhost:53442->localhost:2375 (ESTABLISHED)
docker-co  1359             root    3u  IPv4  20009      0t0  TCP localhost:53438->localhost:2375 (ESTABLISHED)
docker-co  1359             root    4u  IPv4  20019      0t0  TCP localhost:53443->localhost:2375 (ESTABLISHED)
docker-co  1359             root    5u  IPv4  20020      0t0  TCP localhost:53444->localhost:2375 (ESTABLISHED)
docker-co  1359             root    6u  IPv4  19052      0t0  TCP localhost:53445->localhost:2375 (ESTABLISHED)
sshd       1911             root    3u  IPv4 175555      0t0  TCP 10.255.0.1:ssh->172-5-126-131.lightspeed.sntcca.sbcglobal.net:60617 (ESTABLISHED)
sshd       2040          cumulus    3u  IPv4 175555      0t0  TCP 10.255.0.1:ssh->172-5-126-131.lightspeed.sntcca.sbcglobal.net:60617 (ESTABLISHED)
sshd       2514             root    3u  IPv4 179212      0t0  TCP 10.255.0.1:ssh->172-5-126-131.lightspeed.sntcca.sbcglobal.net:60630 (ESTABLISHED)
sshd       2515             sshd    3u  IPv4 179212      0t0  TCP 10.255.0.1:ssh->172-5-126-131.lightspeed.sntcca.sbcglobal.net:60630 (ESTABLISHED)
ssh       25035             root    3u  IPv6 126602      0t0  TCP localhost:35072->localhost:ssh (ESTABLISHED)
sshd      25036             root    3u  IPv6 126603      0t0  TCP localhost:ssh->localhost:35072 (ESTABLISHED)
sshd      25079          cumulus    3u  IPv6 126603      0t0  TCP localhost:ssh->localhost:35072 (ESTABLISHED)

```
## ping6 -I %DP %6I2
```

unknown host

```
```

ping6: invalid option -- '-'
Usage: ping6 [-aAbBdDfhLnOqrRUvV] [-c count] [-i interval] [-I interface]
             [-l preload] [-m mark] [-M pmtudisc_option]
             [-N nodeinfo_option] [-p pattern] [-Q tclass] [-s packetsize]
             [-S sndbuf] [-t ttl] [-T timestamp_option] [-w deadline]
             [-W timeout] destination

unknown host

```
## traceroute www.google.com
```

traceroute to www.google.com (74.125.202.103), 30 hops max, 60 byte packets
 1  10.255.0.3 (10.255.0.3)  0.701 ms  0.589 ms  0.213 ms
 2  100.96.0.1 (100.96.0.1)  0.872 ms  0.766 ms  0.651 ms
 3  io-in-f103.1e100.net (74.125.202.103)  1.951 ms  1.742 ms  1.096 ms

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

traceroute to www.google.com (74.125.202.103), 30 hops max, 60 byte packets
 1  10.255.0.3 (10.255.0.3)  0.701 ms  0.589 ms  0.213 ms
 2  100.96.0.1 (100.96.0.1)  0.872 ms  0.766 ms  0.651 ms
 3  io-in-f103.1e100.net (74.125.202.103)  1.951 ms  1.742 ms  1.096 ms

```
## arp -a
```

spine01 (192.168.0.21) at 44:38:39:00:06:00 [ether] on eth1
server04 (192.168.0.34) at 44:38:39:00:0b:00 [ether] on eth1
leaf01 (192.168.0.11) at 44:38:39:00:02:00 [ether] on eth1
server03 (192.168.0.33) at 44:38:39:00:0a:00 [ether] on eth1
leaf04 (192.168.0.14) at 44:38:39:00:05:00 [ether] on eth1
server01 (192.168.0.31) at 44:38:39:00:08:00 [ether] on eth1
? (169.254.0.1) at 44:38:39:00:03:07 [ether] PERM on eth3
server02 (192.168.0.32) at 44:38:39:00:09:00 [ether] on eth1
leaf03 (192.168.0.13) at 44:38:39:00:04:00 [ether] on eth1
leaf02 (192.168.0.12) at 44:38:39:00:03:00 [ether] on eth1
? (169.254.0.1) at 44:38:39:00:02:07 [ether] PERM on eth2
spine02 (192.168.0.22) at 44:38:39:00:07:00 [ether] on eth1
? (10.255.0.3) at 2c:c2:60:ff:00:4d [ether] on eth0

```
```

nohup: failed to run command ‘arp’: No such file or directory

```
## arp -d %4I1
```

%4I1: Unknown host

```
```

nohup: failed to run command ‘arp’: No such file or directory

```
## ip link set arp off dev %DP
```

Cannot find device "%DP"

```
```

Error: either "dev" is duplicate, or "--help" is a garbage.

Cannot find device "%DP"

```
## sudo mz %DP -A 11.0.0.1 -B 11.0.0.2 -c 2 -v -t tcp dp=23-24
```


Mausezahn 0.40 - (C) 2007-2010 by Herbert Haas - http://www.perihel.at/sec/mz/
Use at your own risk and responsibility!
-- Verbose mode --

 mz/getopts: libnet_init() failed (libnet_check_iface() ioctl: No such device
) Invalid command line parameters!

Mausezahn 0.40 - (C) 2007-2010 by Herbert Haas - http://www.perihel.at/sec/mz/
|
| USAGE: mz [options] [interface] keyword | arg_string | hex_string
|
| Short option description (see doc or manpage for more information):
|  -h                    Prints this information.
|  -c <count>            Send the packet count times (default: 1, infinite: 0).
|  -d <delay>            Apply delay between transmissions. The delay value can be
|                        specified in usec (default, no additional unit needed), or in
|                        msec (e. g. 100m or 100msec), or in seconds (e. g. 100s or 100sec).
|  -r                    Multiplies the specified delay with a random value.
|  -p <length>           Pad the raw frame to specified length (using random bytes).
|  -a <Src_MAC|keyword>  Use specified source mac address, no matter what has
|                        been specified with other arguments. Keywords see below.
|                        Default is own interface MAC.
|  -b <Dst_MAC|keyword>  Same with destination mac address.
|                        Keywords are: 
|          rand            use a random MAC address
|          bc              use a broadcast MAC address
|          own             use own interface MAC address (default for source MAC)
|          stp             use IEEE 802.1d STP multicast address
|          cisco           use Cisco multicast address as used for CDP, VTP, or PVST+
|  -A <Src_IP>           Use specified source IP address (default is own interface IP).
|  -B <Dst_IP|DNS_name>  Send packet to specified destination IP or domain name.
|  -P <ASCII Payload>    Use the specified ASCII payload.
|  -f <filename>         Read the ASCII payload from a file.
|  -F <filename>         Read the hexadecimal payload from a file.
|  -Q <[CoS:]vlan>       Specify 802.1Q VLAN tag and optional Class of Service. You can
|                        specify multiple 802.1Q VLAN tags (QinQ...) by separating them
|                        via a comma or a period (e. g. '5:10,20,2:30').
|  -t <packet_type>      Specify packet type for autobuild (you don't need to care for
|                        encapsulations in lower layers. Most packet types allow/require
|                        additional packet-specific arguments in an arg_string.
|                        Currently supported types: arp, bpdu, cdp, ip, icmp, udp, tcp,
|                        dns, rtp, syslog, lldp.
|                        For context-help use 'help' as arg_string!
|  -T <packet_type>      Specify packet type for server mode. Currently only rtp is supported.
|                        Enter -T help or -T rtp help for further information.
|  -M <MPLS label>       Insert a MPLS label. Enter '-M help' for a syntax description.
|  -v|V                  Verbose and more verbose mode
|  -q                    Quiet mode, i. e. even omit 'important standard short messages'.
|  -S                    Simulation mode: DOES NOT put anything on the wire. This is
|                        typically combined with one of the verbose modes (v or V).


```
```

mz: invalid option -- '-'
 mz/getopts: Option -c requires an argument.
 Invalid command line parameters!

Mausezahn 0.40 - (C) 2007-2010 by Herbert Haas - http://www.perihel.at/sec/mz/
|
| USAGE: mz [options] [interface] keyword | arg_string | hex_string
|
| Short option description (see doc or manpage for more information):
|  -h                    Prints this information.
|  -c <count>            Send the packet count times (default: 1, infinite: 0).
|  -d <delay>            Apply delay between transmissions. The delay value can be
|                        specified in usec (default, no additional unit needed), or in
|                        msec (e. g. 100m or 100msec), or in seconds (e. g. 100s or 100sec).
|  -r                    Multiplies the specified delay with a random value.
|  -p <length>           Pad the raw frame to specified length (using random bytes).
|  -a <Src_MAC|keyword>  Use specified source mac address, no matter what has
|                        been specified with other arguments. Keywords see below.
|                        Default is own interface MAC.
|  -b <Dst_MAC|keyword>  Same with destination mac address.
|                        Keywords are: 
|          rand            use a random MAC address
|          bc              use a broadcast MAC address
|          own             use own interface MAC address (default for source MAC)
|          stp             use IEEE 802.1d STP multicast address
|          cisco           use Cisco multicast address as used for CDP, VTP, or PVST+
|  -A <Src_IP>           Use specified source IP address (default is own interface IP).
|  -B <Dst_IP|DNS_name>  Send packet to specified destination IP or domain name.
|  -P <ASCII Payload>    Use the specified ASCII payload.
|  -f <filename>         Read the ASCII payload from a file.
|  -F <filename>         Read the hexadecimal payload from a file.
|  -Q <[CoS:]vlan>       Specify 802.1Q VLAN tag and optional Class of Service. You can
|                        specify multiple 802.1Q VLAN tags (QinQ...) by separating them
|                        via a comma or a period (e. g. '5:10,20,2:30').
|  -t <packet_type>      Specify packet type for autobuild (you don't need to care for
|                        encapsulations in lower layers. Most packet types allow/require
|                        additional packet-specific arguments in an arg_string.
|                        Currently supported types: arp, bpdu, cdp, ip, icmp, udp, tcp,
|                        dns, rtp, syslog, lldp.
|                        For context-help use 'help' as arg_string!
|  -T <packet_type>      Specify packet type for server mode. Currently only rtp is supported.
|                        Enter -T help or -T rtp help for further information.
|  -M <MPLS label>       Insert a MPLS label. Enter '-M help' for a syntax description.
|  -v|V                  Verbose and more verbose mode
|  -q                    Quiet mode, i. e. even omit 'important standard short messages'.
|  -S                    Simulation mode: DOES NOT put anything on the wire. This is
|                        typically combined with one of the verbose modes (v or V).



Mausezahn 0.40 - (C) 2007-2010 by Herbert Haas - http://www.perihel.at/sec/mz/
Use at your own risk and responsibility!
-- Verbose mode --

 mz/getopts: libnet_init() failed (libnet_check_iface() ioctl: No such device
) Invalid command line parameters!

Mausezahn 0.40 - (C) 2007-2010 by Herbert Haas - http://www.perihel.at/sec/mz/
|
| USAGE: mz [options] [interface] keyword | arg_string | hex_string
|
| Short option description (see doc or manpage for more information):
|  -h                    Prints this information.
|  -c <count>            Send the packet count times (default: 1, infinite: 0).
|  -d <delay>            Apply delay between transmissions. The delay value can be
|                        specified in usec (default, no additional unit needed), or in
|                        msec (e. g. 100m or 100msec), or in seconds (e. g. 100s or 100sec).
|  -r                    Multiplies the specified delay with a random value.
|  -p <length>           Pad the raw frame to specified length (using random bytes).
|  -a <Src_MAC|keyword>  Use specified source mac address, no matter what has
|                        been specified with other arguments. Keywords see below.
|                        Default is own interface MAC.
|  -b <Dst_MAC|keyword>  Same with destination mac address.
|                        Keywords are: 
|          rand            use a random MAC address
|          bc              use a broadcast MAC address
|          own             use own interface MAC address (default for source MAC)
|          stp             use IEEE 802.1d STP multicast address
|          cisco           use Cisco multicast address as used for CDP, VTP, or PVST+
|  -A <Src_IP>           Use specified source IP address (default is own interface IP).
|  -B <Dst_IP|DNS_name>  Send packet to specified destination IP or domain name.
|  -P <ASCII Payload>    Use the specified ASCII payload.
|  -f <filename>         Read the ASCII payload from a file.
|  -F <filename>         Read the hexadecimal payload from a file.
|  -Q <[CoS:]vlan>       Specify 802.1Q VLAN tag and optional Class of Service. You can
|                        specify multiple 802.1Q VLAN tags (QinQ...) by separating them
|                        via a comma or a period (e. g. '5:10,20,2:30').
|  -t <packet_type>      Specify packet type for autobuild (you don't need to care for
|                        encapsulations in lower layers. Most packet types allow/require
|                        additional packet-specific arguments in an arg_string.
|                        Currently supported types: arp, bpdu, cdp, ip, icmp, udp, tcp,
|                        dns, rtp, syslog, lldp.
|                        For context-help use 'help' as arg_string!
|  -T <packet_type>      Specify packet type for server mode. Currently only rtp is supported.
|                        Enter -T help or -T rtp help for further information.
|  -M <MPLS label>       Insert a MPLS label. Enter '-M help' for a syntax description.
|  -v|V                  Verbose and more verbose mode
|  -q                    Quiet mode, i. e. even omit 'important standard short messages'.
|  -S                    Simulation mode: DOES NOT put anything on the wire. This is
|                        typically combined with one of the verbose modes (v or V).


```
