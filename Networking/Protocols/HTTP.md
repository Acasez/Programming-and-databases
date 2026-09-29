Hypertext Transfer Protocol is one of the most common protocols of the [[Application Layer|application layer]] of the internet, used on most web pages. **HTTPS** Hypertext Transfer Protocol Secure, is a newer variant with more security features. HTTP forms URL, Uniform Resource Locator

HTTP is stateless, it maintains no information about past requests. States are complex

HTTP uses [[TCP]], creating a TCP connection to port 80.

Non-Persistent HTTP vs Persistent HTTP
One object sent over TCP vs Multiple objects sent over TCP connection.

| Non-Persistent HTTP      | Persistent HTTP                           |
| ------------------------ | ----------------------------------------- |
| One object sent over TCP | Multiple objects sent over TCP connection |
| Old, first versions      | Current modern system                     |
| Slow download speed      | Faster download speed                     |

URLs can be broken down into two parts, hostname and domain. 

There are two types of HTTP message methods, [[HTTP Request]] and [[HTTP Response]]

### HTTP/2 (2015)
Decreased delay in multi-object HTTP requests.
Increased flexibility at server in sending objects to client.
Breaks up larger objects into frames to do so.
Server can figure out to send smaller objects first.
-Still operates over a single TCP connection and has no encryption.
### HTTP/3 (2022)
Adds security, 
Handles error and congestion control per object
Uses QUIC + UDP instead of TCP


| Name       | HTTP                             | DNS                      |
| ---------- | -------------------------------- | ------------------------ |
| Full Name  | Hypertext Transfer Protocol      | Domain Name System       |
| Used For   | Sending data across the internet | Looking up web addresses |
| Port       | 80 (443 for HTTPS)               | 53                       |
| Data Types | HTML, images, videos, multimedia | Domain, IP Mapping       |
|            |                                  |                          |

