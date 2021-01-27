---
title: dns
layout: default
parent: Network
grand_parent: Cheat Sheet
nav_order: 4
---
## dns

Pod DNS Name

Easiest way for lookup is dumping /etc/resolv.conf

```bash
sh-4.2# cat /etc/resolv.conf
search test.svc.cluster.local svc.cluster.local cluster.local eu-west-1.compute.internal
nameserver 172.30.0.10
options ndots:5
```

So this pod can be reached via <name>.test.svc.cluster.local with <name> being the deployment name and test being the namespace.



