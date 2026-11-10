Match multiple packet-header fields, instead of traditional [[IP Address]] destination based forwarding. Sits in [[Middlebox|middleboxes]]. Many headers fields create multiple possible actions. 
- Forward
- Drop
- Multiply
- Redirect

We can have the network
- Block suspicious traffic (based on source IP, destination port etc)
- Redirect selected traffic flows
- Prioritize delay-sensitive traffic. 

OpenFlow is one of the first software defined networking (SDN) standards (2008). P4 is a domain-specific language for programming packet-process behavior. 

Uses a Flow table defined by header field values. Match patterns, do actions, set priority.
Can set up [[Firewalls|firewalls]]. Can also be use to setup [[NAT]] services

![[Pasted image 20261012094909.png]]
