---
aliases:
  - authenticate
  - authentication
---
Prove identity in [[Network Security]].

Can check source IP.. (Ap 2.0)
	Can be spoofed

Can also include password. (Ap 3.0)
	Can listen in and learn password and then spoof it.

Can also include password encrypted. (Ap 3.1)
	Can listen in and send encrypted password and then spoof it.

Can require the sender to send back a random value modified by shared key (nonce) (Ap 4.0)
	Requires symmetric key

Use nonce and public key to set up communication. (Ap 5.0)
	Can do a man in the middle attack, pretending to be other partner to get keys.



