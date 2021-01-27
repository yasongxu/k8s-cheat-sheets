---
title: dns
layout: default
parent: Kubernetes
grand_parent: Cheat Sheet
---
## dns

## CoreDNS

Adding an external nameserver
This is done using the forward plugin. Add a server section to your Corefile like this

```
.example.net:53 {
forward . 1.1.1.1
}
```

this would resolve example.net via Cloudflare DNS.