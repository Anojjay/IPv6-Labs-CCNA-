
# IPv6 Static Routing Lab

## Project Overview

Configured and tested an IPv6 network in Cisco Packet Tracer using three routers, two switches, and two end devices.

The lab focused on implementing IPv6 static routing, SLAAC, and a redundant backup path between PC1 and PC2.

## What I Did

- Enabled IPv6 unicast routing on R1, R2, and R3
- Configured PC1 and PC2 to obtain IPv6 addresses using SLAAC
- Configured IPv6 static routes between the networks
- Implemented floating static routes as backup paths
- Used IPv6 link-local addresses as next-hop addresses
- Verified routing using `show ipv6 route`
- Tested end-to-end connectivity using `ping`
- Used `tracert` to verify the routing path
- Tested network redundancy by removing the primary R1–R3 connection

## Network Topology

**PC1 → R1 → R3 → PC2**

Primary path:

```text
PC1 → R1 → R3 → PC2
