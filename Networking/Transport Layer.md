---
aliases:
  - transport
  - transport layer
  - Transport
---
The transport layer is second highest [[Layering Networks|layer]] of [[The Internet]], underneath the [[Application Layer]]. 

The quality, timing, security, and quantity of data transfer required depends on the application.

There are two transport services on the internet, [[TCP]] and [[UDP]]

|                     | TCP      | UDP        |
| ------------------- | -------- | ---------- |
| Data Transfer       | Reliable | Not always |
| Flow Control        | Yes      | No         |
| Congestion Control  | Yes      | No         |
| Connection Oriented | Yes      | No         |
| Timing Guarentee    | No       | No         |
| Minimum Throughput  | No       | No         |
| Security            | No       | No         |
Can build services on top UDP, making it extendable

Vanilla TCP & UDP has no security features, no encryption
Transport Layer Security, TLS, is commonly used.
	Provides encrypted TCP connections, data integrity and and end point authentication. 


![[Pasted image 20260924094810.png]]