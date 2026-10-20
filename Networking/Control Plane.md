---
aliases:
  - control plane
  - Control
---
The Control Plane is one of two "planes" of the [[Network Layer|network layer]] that handles routing. The control plane tries to figure out the best route, based on values like speed, path, 

[[Programmable Networks]] operate here, to calculate the best path using info from packet headers and [[Routers|routers]].

| [[Data Plane]] | Control Plane      |
| -------------- | ------------------ |
| Local          | Network wide       |
| Forwarding     | Routing            |
|                | Routing algorithms |

Different types routing algorithms. 
![[Pasted image 20261013091842.png]]
![[Pasted image 20261013092337.png]]
Use Dijkstra's algorithm to calculate best path. Bellman-Ford algorithm can also be used sometimes
![[Pasted image 20261013102851.png]]