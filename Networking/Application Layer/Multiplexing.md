Multiplexing and demultiplexing are techniques used in the across multiple layers, but primarily in [[Application Layer|application layer]] to send more efficient packets by merging messages from different applications into the same packet. [[TCP]] and [[UDP]] both do multiplexing.

Demultiplexing happens before the [[Socket|socket]]s so sockets get the correct information. . 

*Multiplexing and demultiplexing is kind of like on and off ramps on highways.*

UDP demultiplexing, checking [[Port Number|port numbers]] (source and destination) and inverting them

TCP demultiplexing, [[IP Address]] and port number.
4-tuple
- source IP address
- source port number
- destination IP address
- destination port number