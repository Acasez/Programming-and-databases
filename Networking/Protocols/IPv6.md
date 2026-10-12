IPv6 is the latest version of [[IP]] designed to handle limited IPv4 [[IP Address]] space.

It also simplifies packet process
• Removes the header checksum and router fragmentation (e.g. no checksum
update when Hop Limit decreases)
• enable different network-layer treatment of “flows”
• Introduces a Flow label to help routers identify and distinguish traffic flows

The IPv6 datagram format is below

![[Pasted image 20261012092154.png]]

There is no way to upgrade all IPv4 networks to IPv6 at once. We have to operate both of them at once, "tunneling". 
50% of clients use IPv6 today, and new networks almost always use it.

