Packet delay is the time it takes for a [[Packet]] to travel to and from a [[Routers|router]] and is split into for categories. 


| Name             | Time         | Step | Key   |
| ---------------- | ------------ | ---- | ----- |
| Nodal Processing | Microseconds | 1    | proc  |
| Queuing          | Varying      | 2    | queue |
| Transmission     | Varying      | 3    | trans |
| Propogation      | Milliseconds | 4    | prop  |

Routers are very fast, Nodal Processing from the router is very fast measured in microseconds.

Queuing delay. Depends on the congestion level of the router. 
a: average packet arrival rate.
L: packet length (bits)
R: link bandwidth (bit transmission rate)
$$
(L a) /R
$$

Transmission delay. Depends on the size of the packet and speed of router.

Propagation delay comes from the time the package takes to transfer. As packets generally transfer at light speed this is measured in milliseconds. 

**Caravan example** - Transmission is tollbooth, propagation is car speed.  

Packet delay can be measured with the **traceroute** program.
It sends three packets to the router and measures the Round Trip Time (RTT) for the reply of each packet.

**Throughput** 
The rate (bits/time) which bits are sent from sender to receiver. *Can use a water pipe as an analogy.*
- Instant throughput is the rate measured once.
- Average throughput is measured over longer time period
Throughput is limited by smallest transmission capacity, the bottleneck link which tend to be at the edge of the network.




