---
aliases:
  - MAC
  - MACs
  - Multiple access protocols
  - multiple access protocols
---
Multiple access protocols (MAC) are protocols set up to avoid collisions of packets in the [[Link Layer|link]] layer.

There are three types of MAC protocols


| Name                 | How                                | Used        | Protocols            | Overhead | Wait Time |
| -------------------- | ---------------------------------- | ----------- | -------------------- | -------- | --------- |
| Channel Partitioning | Divide channel into smaller pieces |             | TDMA, FDMA           |          | Yes       |
| Random Access        | Expect collisions, then detect     | Widely Used | ALOHA; CSMA, CSMA/CA |          |           |
| Taking Turns         | Nodes takes turns                  |             | Bluetooth, FDDI      | Yes      | Yes       |

CSMA, Carrier sense multiple access. Newer protocols, better than ALOHA

Taking turns, polling vs token based



![[Pasted image 20261102093504.png]]