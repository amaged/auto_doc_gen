# vtysh
## cl-rctl
```

nohup: failed to run command ‘cl-rctl’: No such file or directory

```
```

nohup: failed to run command ‘cl-rctl’: No such file or directory

```
## ip route
```

default via 10.255.0.3 dev eth0 
10.0.0.11 via 169.254.0.1 dev eth2  proto bgp  metric 20 onlink 
10.0.0.12 via 169.254.0.1 dev eth3  proto bgp  metric 20 onlink 
10.0.0.13  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.0.0.14  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.0.0.21  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
10.0.0.22  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
10.0.0.31  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.0.0.32  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.0.0.33  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.0.0.34  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.244.6.0/26  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.244.40.192/26  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.244.135.128/26  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.244.188.0/26  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.255.0.0/16 dev eth0  proto kernel  scope link  src 10.255.0.1 
172.17.0.0/16 dev docker0  proto kernel  scope link  src 172.17.0.1 dead linkdown 
192.168.0.0/16 dev eth1  proto kernel  scope link  src 192.168.0.254 

```
```

Command "--help" is unknown, try "ip route help".

default via 10.255.0.3 dev eth0 
10.0.0.11 via 169.254.0.1 dev eth2  proto bgp  metric 20 onlink 
10.0.0.12 via 169.254.0.1 dev eth3  proto bgp  metric 20 onlink 
10.0.0.13  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.0.0.14  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.0.0.21  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
10.0.0.22  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
10.0.0.31  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.0.0.32  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.0.0.33  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.0.0.34  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.244.6.0/26  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.244.40.192/26  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.244.135.128/26  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.244.188.0/26  proto bgp  metric 20 
	nexthop via 169.254.0.1  dev eth2 weight 1 onlink
	nexthop via 169.254.0.1  dev eth3 weight 1 onlink
10.255.0.0/16 dev eth0  proto kernel  scope link  src 10.255.0.1 
172.17.0.0/16 dev docker0  proto kernel  scope link  src 172.17.0.1 dead linkdown 
192.168.0.0/16 dev eth1  proto kernel  scope link  src 192.168.0.254 

```
## cl-ospf neighbor
```

nohup: failed to run command ‘cl-ospf’: No such file or directory

```
```

nohup: failed to run command ‘cl-ospf’: No such file or directory

```
## cl-bgp summary
```

nohup: failed to run command ‘cl-bgp’: No such file or directory

```
```

nohup: failed to run command ‘cl-bgp’: No such file or directory

```
## cl-bgp route
```

nohup: failed to run command ‘cl-bgp’: No such file or directory

```
```

nohup: failed to run command ‘cl-bgp’: No such file or directory

```
