---
aliases:
  - transport
  - transport layer
  - Transport
---
The transport layer is second highest [[Layering Networks|layer]] of [[The Internet]], underneath the [[Application Layer|application layer]]. 

The quality, timing, security, and quantity of data transfer required depends on the application. We want [[Reliable Data Transfer|reliable data transfer]], but in reality that is hard. Doing an "[[Handshake|handshake]]" is one way to make the data transfer more reliable. 

There are two transport services on the internet, [[TCP]] and [[UDP]]

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

Vanilla TCP & UDP has no security features, no encryption
Transport Layer Security, TLS, is commonly used.
	Provides encrypted TCP connections, data integrity and and end point authentication. 


![[Pasted image 20260924094810.png]]

Increasingly, many are moving flow control to the application layer (QUIC).

