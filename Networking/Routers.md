---
aliases:
  - router
  - routers
---
The Internet's [[Network Core|network core]] is composed of a mesh of routers, that handle communication between them. Routers provide two key actions to send [[Packet|packets]] to their correct destination, by [[Network Address|network addresses]]

| Name                 | Type   | Desc                                                       | Plane                      |
| -------------------- | ------ | ---------------------------------------------------------- | -------------------------- |
| Forwarding/Switching | Local  | Move packets from router input link to correct output link | [[Data Plane\|Data]]       |
| [[Routing]]          | Global | Determining source to destination path by packets          | [[Control Plane\|Control]] |

Routing is deciding the whole route, forwarding is going the correct way at each router.
Trip planning vs intersections.

Routers are often slower ethernet cables, limiting internet speeds. If many packets are being sent across routers, it forms a **queue** as routers can only send a package at a time. Routers have a limited memory space, if a queue becomes to full it might drop the packet, causing [[Packet Loss]]

Routers have input ports, output ports, switching fabric and routing processors

![[Pasted image 20261006092220.png]]

![[Pasted image 20261006092448.png]]
Routers use Longest prefix matching when forwarding, using the longest address prefix that matches the destination. 
