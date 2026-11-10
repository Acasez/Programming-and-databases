---
aliases:
  - routing
---
Routing is the act of determining the source to destination path, its one of two key actions of [[Routers|routers]]. Routing happens in the [[Control Plane|control plane]] of the [[Network Layer|network layer]]


Routing can be within or between domains, with gateways connecting them.

| Type         | AS       | Desc.                           | Edge           |
| ------------ | -------- | ------------------------------- | -------------- |
| Intra Domain | Intra-AS | Routing within a domain system. | Gateway Router |
| Inter Domain | Inter-AS | Routing between systems         |                |
Intra Domain Protocols

| Abbr     | Name                                       | Type               | Use         | Invented |
| -------- | ------------------------------------------ | ------------------ | ----------- | -------- |
| RIP      | Routing Information Protocol               | Distant Vector     | Not anymore | 1980s    |
| [[OSPF]] | Open Shortest Path First                   | Link state routing | Widely      | 1989     |
| EIGRP    | Enhanced Interior Gateway Routing Protocol | Distant Vector     |             | 2010s    |
For Inter domain protocols, [[BGP]] is the dominant one




