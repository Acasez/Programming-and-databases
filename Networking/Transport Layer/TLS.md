[[Transport Layer]] security is a widely used [[Network Security|network security]] protocol supported by almost all browsers and web servers. TLS is considered a transport layer network, but sits in the application layer. It's integrated in [[QUIC]]

It provides  
- confidentiality - via [[Symmetric Key|symmetric key]] encryption
- integrity - via [[Cryptography|cryptographic]] hashing
- authentication - via [[Public Key|public key]] cryptography

It uses an extra [[Handshake|handshake]] on top of the standard one, to share keys. 

It's considered bad practiced to use the same key for more than one cryptographic function. Generate new keys after doing each one.

Data stream as a series of secure record. Includes sequence numbers in record to prevent man in the middle attacks.

Includes special message to close connection to prevent attackers from forcing early closure.

