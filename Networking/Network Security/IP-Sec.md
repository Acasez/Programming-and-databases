[[IP]] Security Protocol provides [[Datagram|datagram]] level [[Network Security|network security]] - encryption, authentication, integrity.

Transport mode and tunnel mode.

| Transport Mode            | Tunnel Mode                                 |
| ------------------------- | ------------------------------------------- |
| Protects datagram payload | Entire datagram is encrypted                |
|                           | Datagram is encapsulated with new IP header |
|                           | Tunnels directly to desination              |
|                           | Used in [[VPN]]s                            |
Tunnel mode sets up a security association, on tunnel.

IP is connectionless, IP-Sec is connection oriented. 

It uses sequence numbers as well, like TLS.

Manual keying is impractical, uses IKE (Internet Key Exchange instead)




