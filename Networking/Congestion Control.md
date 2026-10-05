---
aliases:
  - congestion
  - Congestion
  - congestion control
---
Informally: “too many sources sending too much data too fast for
network to handle”

Can lead to [[Packet Delay]] and [[Packet Loss]]

Happens when routers reach close or to max capacity. Router can't handle the throughput.
Since router buffers aren't infinite, packets get dropped and needs to be retransmitted increasing congestion. Start routers won't have perfect longer of router throughput/buffer, causing more problems like extra packages sent, lost or duplicated packages.

![[Pasted image 20261005092437.png]]

In reality there is more than one router, further increasing the complexity and risks of congestion. If packets get dropped at later links, we will have wasted the capacity at earlier routers.
![[Pasted image 20261005093634.png]]

**Other solutions**
### End-to-end congestion control
Infer congestion from observed loss, delay
![[Pasted image 20261005094057.png]]
### Network assisted congestion control
Routers provide feedback on [[Packet|packets]], set as the ECE bit. Involves both IP and TCP. 
![[Pasted image 20261005094111.png]]
![[Pasted image 20261005101316.png]]
### AIMD
Increase sending rate until congestion occurs then decrease packet. Probing for bandwidth
![[Pasted image 20261005095013.png]]
TCP Reno vs Timeout![[Pasted image 20261005095212.png]]
### TCP Cubic
Improvement on TCP Reno, increase faster in the beginning, then flatten to increase throughput. Curves instead of the sawtooth.
### Delay-based TCP congestion control


![[Pasted image 20261005100928.png]]

