The client-server architecture is the oldest model of [[Application Layer|application layer]] communication. 

Email is a good example of the client-server paradigm, with email clients as the user clients and mail servers as server. Email uses the SMTP protocol between email client and server, [[TCP]] between mail servers and IMAP (or others) for getting emails from mail servers to clients. 

Servers 
- are always on hosts
- permanent IP addresses.
- often in data centers for scaling.

Clients 
- communicate with server
- not always on
- may have dynamic IP addresses
- don't communicate directly with other clients
 