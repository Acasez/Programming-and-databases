Internet control message protocol is a hosts and [[Routers|routers]] to communicate network level information to each other. Also used in ping and [[Traceroute|traceroute]]

| Ping                                                    | Traceroute                                                           |
| ------------------------------------------------------- | -------------------------------------------------------------------- |
| Echo Request,                                           | Probes with increasing TTL values                                    |
| Can I reach this destination and how long does it take? | Which routers does traffic encounter on the path to the destination? |


Used in the [[Network Layer|network layer]] "above" [[IP]], carried by IP [[Datagram|datagrams]]. Protocol number 1.

Has a 1 byte type field, 1 byte code field, 2 byte checksum field, and 8 byte header.



