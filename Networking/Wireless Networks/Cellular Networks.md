---
aliases:
  - cellular network
  - cellular networks
---
Cellular Networks are a form of [[Wireless Networks|wireless network]]. 
4G/5G

Share a lot of similarities with the wired internet.
Network of networks
Uses a lot of protocols, HTTP, DNS, TCP, IP, NAT
Separation of data/control planes

Works on a wireless [[Link Layer|link layer]]. 
Mobility is a 1st class service.
User identity via SIM cards
business model, users subscribe to a cellular provider 

4G LTE architecture connect via radio access network
64-bit International Mobile Subscriber Identity (IMSI)

Base stations at the edge of the network.
Helps user mobility, keep track of where users are connection.

Home Subscriber Service (HSS) stores all information about the mobile device for which the HSS is their home network.
- Store roaming info
- Authentication info
- When not on [[Home Network|home network]], device is [[Roaming]]

Mobility Management Entity (MMS), works with the HSS

Two gateways. 
Serving Gateway - Tracks all mobile devices on the mobile network.
PDN Gateway - Gateway to [[The Internet]], works like a router.

Cellular networks also have their own control/data plane separation.

![[Pasted image 20261103100908.png]]