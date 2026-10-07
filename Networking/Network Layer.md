---
aliases:
  - network
  - network layer
  - Network
---
The network layer is the third [[Layering Networks|layer]] of The Internet, below the [[Transport Layer|transport]] layer. Most of the network layer uses the [[IP]] protocol

Network layer protocols in every internet device.

[[Routers]] operate on the network layer

The network layer can be split up into two parts, the Data Plane and the Control Plane

| Data Plane | Control Plane      |
| ---------- | ------------------ |
| Local      | Network wide       |
| Forwarding | Routing            |
|            | Routing algorithms |
|            |                    |

Forwarding Table VS Software-Defined Networking (SDN)
Routing algorithms in every router vs remote controllers


| Network Architecture | Service Model      | Bandwidth      | Loss     | Order    | Timing |
| -------------------- | ------------------ | -------------- | -------- | -------- | ------ |
| Internet             | Best Effort        | none           | no       | no       | no     |
| ATM                  | Constant Rate      | Constant Rate  | yes      | yes      | yes    |
| ATM                  | Guaranteed min     | Guaranteed min | no       | yes      | no     |
| Internet             | Intserv Guarenteed | Yes            | yes      | yes      | yes    |
| Internet             | Diffserv           | possible       | possibly | possibly | no     |

There is also the the minor ICMP protocol for debugging. 

