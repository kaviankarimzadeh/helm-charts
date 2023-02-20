Cilium:

#configuration changed from default:

```
ipam:
  mode: "kubernetes"
  operator:
    # IPv4 CIDR range to delegate to individual nodes for IPAM.
    clusterPoolIPv4PodCIDR: "10.244.0.0/16"
```
