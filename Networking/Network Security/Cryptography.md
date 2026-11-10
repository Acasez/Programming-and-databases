---
aliases:
  - cryptography
  - cryptographic
---
Cryptography is the art of encoding messages using algorithms so they can be decoded later, and not be read by third parties. Used in [[Encryption]]

Interceptors only see the ciphertext which is unreadable without the key. Can try to break the encryption using a few methods.
- Brute Force
- Statistical analysis
- Known plaintext attack

Need to protect the keys, otherwise encryption is pointless.

There are two main methods of cryptography [[Symmetric Key]] and [[Public Key]]. 
Symmetric key crypto is far faster, but there is no great way to initially share symmetric keys, leading to a scenario where public key crypto is first used and then symmetric key for the rest.

Public key Certification Authorities. (CA)
