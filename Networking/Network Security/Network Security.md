---
aliases:
  - network security
---
[[The Internet]] architecture wasn't designed with security in mind
Original vision: "A group of mutually trusting users attached to a transparent network"

Common attack types

| Name                    | Desciption                                                           | Defense                                |
| ----------------------- | -------------------------------------------------------------------- | -------------------------------------- |
| Packet Sniffing         | Get copies of a packet passing by                                    | [[Encryption]], Access Control         |
| IP Spoofing             | Inject packets with false source address.                            | [[Authentication]], digital signatures |
| Denial of Service (DoS) | Make resources unavailable by overwhelming with bogus traffic        | [[Firewalls]]                          |
| Man in the middle       | Pretend to be one of two communication partners to get keys and info | [[TLS]]                                |

Denial of Service (DoS) - Often break into other hosts, then launch coordinated attack, Distributed Denial of Service (DDoS) attack.

**The Goal - Security by design**

- Confidentiality: Only sender and indented recover should understand message contents
- Authentication: Sender, receiver want to confirm identify of each other
- Message Integrity: Message not altered
- Access Control: Only authorized users can access marked resources
- Availability: Users have access to resources they should be able to reach.

Privacy is not one of these directly, but is of course very important.

