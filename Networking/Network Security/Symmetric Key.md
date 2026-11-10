---
aliases:
  - symmetric key
---
Symmetric key [[Cryptography|cryptography]] is the second of the two main methods of [[Encryption]]

Symmetric key crypto -Sender and receiver has the same key
	- Data Encryption Standard (DES), encryption standard. 56-bit key, 64 bit block, skip every 8th bit in key
		- Obsolete, Not safe now, can easily be brute forced. 
	- 3DES, applies three times, bit better, still can be brute forced.
	- Advanced Encryption Standard (AES), new standard. 128 bit blocks.
		- Brute forcing takes much longer
	- Requires both sender and receiver know shared key, how do to that securely?
		- Diffie-Hellman key exchange. Two parties share key over an insecure channel