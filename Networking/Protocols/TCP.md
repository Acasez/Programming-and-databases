Transmission Control Protocol is the most common [[Protocols|protocol]] of the [[Transport Layer|transport layer]]. 
TCP provides reliable, byte stream.

|                     | TCP                   | UDP                  |
| ------------------- | --------------------- | -------------------- |
| Data Transfer       | Reliable              | Not always           |
| Flow Control        | Yes                   | No                   |
| Congestion Control  | Yes                   | No                   |
| Connection Oriented | Yes                   | No                   |
| Timing Guarantee    | No                    | No                   |
| Minimum Throughput  | No                    | No                   |
| Security            | No                    | No                   |
| Speed               | Slower                | Faster               |
| Data treated as     | Continues byte stream | Independent messages |
| Used by             | HTTP, HTTPS, SMTP     | DNS, VoIP, Streaming |
| Expandable          | No                    | Yes                  |
TCP segments track ACK for the purpose of [[Reliable Data Transfer|reliable data transfer]]. 

![[Pasted image 20260930141045.png]]
