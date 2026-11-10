---
aliases:
  - reliable data transfer
---
Reliable Data Transfer is the goal of the [[Transport Layer|transport layer]]. 
How does the transfer recover from errors?

To do so we begin with a [[Handshake|handshake]] protocol to confirm a connection.
## RDT 1.0
Can only work on Reliable Data Channels, don't work outside them
## RDT 2.0
For each packet send acknowledgements (ACK) or negative acknowledgements (NAK) to tell the sender weather or not the package was successful. 

- Stop and wait
sender sends one packet, then waits for receiver response

Problem! 
What happens if ACK/NAK corrupted?
▪ sender doesn’t know what happened at receiver!
## RDT 2.1
Uses sequence numbers to know if response was corrupted.
Introduces more states.
## RDT 2.2
Only uses ACK, not NAK
Used to be the approach used by [[TCP]]
## RDT 3.0
Sender waits a "reasonable" amount of time for ACK
Retransmits if no ACK received in time
Has a timeout variable, for when to resend.
Slow, doesn't use data channel most of the time when waiting - Solve with pipelining
## Go-Back-N
Sender sets up a "window" of N, an amount of packages that can be transmitted without being acknowledged. 
Receiver can do a cumulative acknowledgement to acknowledge multiple packets at once

Set an estimated RTT round trip time value, based on average round trip time

![[Pasted image 20260930132605.png]]

![[Pasted image 20260930142530.png]]