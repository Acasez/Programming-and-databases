The User Datagram Protocol is one of two [[Protocols]] on the [[Transport Layer|transport layer]]. 

The UDP doesn't set up a direct connection between client and server, no "handshake". The sender attaches the IP address and port to each [[Packet]].

UDP is more expandable than [[TCP]]
Unreliable, datagram oriented service

| Name                | TCP                           | UDP                      |
| ------------------- | ----------------------------- | ------------------------ |
| Fullname            | Transmission Control Protocol | User Datagram Protocol   |
| Data Transfer       | Reliable                      | Not always               |
| Flow Control        | Yes                           | No                       |
| Congestion Control  | Yes                           | No                       |
| Connection Oriented | Yes                           | No                       |
| Timing Guarantee    | No                            | No                       |
| Minimum Throughput  | No                            | No                       |
| Security            | No                            | No                       |
| Speed               | Slower                        | Faster                   |
| Data treated as     | Continues byte stream         | Independent messages     |
| Used by             | HTTP, HTTPS, SMTP             | [[DNS]], VoIP, Streaming |
| Expandable          | No                            | Yes                      |
