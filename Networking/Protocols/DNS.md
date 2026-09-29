Domain Name System (DNS) is the part of [[The Internet]]s [[Application Layer|application layer]] that maps between host names and IP addresses. DNS often leads to [[HTTP]] addresses, but is a separate thing from them. 

The DNS is a distributed database implemented in the hierarchy of many name servers. 
Core Internet function, implemented in the application layer
Sits at the networks edge. 
Not centralized, due to risk of failure and scale.

| Name       | HTTP                             | DNS                      |
| ---------- | -------------------------------- | ------------------------ |
| Full Name  | Hypertext Transfer Protocol      | Domain Name System       |
| Used For   | Sending data across the internet | Looking up web addresses |
| Port       | 80 (443 for HTTPS)               | 53                       |
| Data Types | HTML, images, videos, multimedia | Domain, IP Mapping       |
|            |                                  |                          |
|            |                                  |                          |

Provides
- hostname to IP address.
- host aliasing
- mail server aliases
- load distribution

Handles trillions of queries each day.


Root servers
	Top level domain (TLD)
		Authorities server
			Local DNS server

The DNS Root server is a core function of the internet. Responsibility of ICANN (Internet Corporation for Assigned Names and Numbers)

...

...

Local DNS is where the clients sends DNS queries. 
---
Querying
Iterative Querying and Responsive Querying
![[Pasted image 20260924104452.png]]
Mapping is often cached to reduce response time and reduce load. 
Caches are kept for a limited time, as server addresses may change over time

DNS Records
Resource Records (RR)

| Type  | Name           | value                               |
| ----- | -------------- | ----------------------------------- |
| A     | hostname       | IP Adress                           |
| NS    | domain         | hostname of authoritive name server |
| CNAME | alias name     | canonical name                      |
| MX    | SMTP mail name | server associetied with name        |

