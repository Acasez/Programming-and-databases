---
aliases:
  - link
  - link layer
  - Link
---
The link layer is the fourth [[Layering Networks|layer]] of The Internet, below the [[Network Layer|network layer]]. It's implemented on every single host, which has a network interface card (NIC) or a chip. The link layer uses [[Multiple Access Protocol|multiple access protocols]] (MAC) to avoid collisions in the link.

Principles:
- error detection
- sharing a broadcast channel, multiple access
- link layer addressing
- local area networks; Ethernet, VLAN

Hosts and routers: Nodes

Communication channel that connect along path - Links
Can be wired or wireless
Transfer on different protocols on different links with different services (reliable vs not)

Physically transfer the datagram from one node to the other.

Packets are called frames, encapsulates [[Datagram|datagrams]].


![[Pasted image 20261102090952.png]]