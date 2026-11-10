---
aliases:
  - traceroute
---
Traceroute is a tool for checking web networks, using [[ICMP]] protocol. It sends three messages with different TTL values (TTL=1, TTL=2 & TTL3), which are then returned. Traceroute is primarily used to check which routers, the traffic encounters on route. When it arrives it sends a message back "port unreachable" (yes, for some reason)

