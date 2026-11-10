---
aliases:
  - proxy servers
  - web caches
---
Web caches are made to satisfy web [[HTTP Request|requests]] without involving the origin server. Instead of always getting the data from the web  server, the user gets stored data from the cache server. Web caches can often be closer to than the clients server, reducing load time. 

HTTP requests go by the cache server, that gets to store data transferred. If the cache then has the data it doesn't need to go to the origin server.
Caches can control how long they can store caches, so it doesn't serve old material.

Web caches are also called proxy servers, and a common part of [[Client Server Architecture]] today.
There are loads of proxy server across the world, reducing loads on the server with data and reducing request times and [[Packet Delay]]
Intuitional networks may cache data to allow very quick requests for selected material.



