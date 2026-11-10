Border Gateway Protocol is the de facto inter-domain [[Routing|routing]] protocol. Its a police based protocol. Can set up things like "don't accept a path that passes through specific ISP or country". Common policy is not restrict "transit traffic" that just passes through AS.

Allows [[Subnet|subnets]] to advertise their existence and destinations they can reach. 

Provides AS
- means to get network reachability for neighboring AS.
- Determines routes to other networks
- Propagate reachability information to internal routers

eBGP runs between routers in different AS
iBGP runs between routers in the same AS

BGP session, two BGP routers ("peers", "speakers") exchange messages over semi-permanent [[TCP]] connections, advertising paths to each other.

**BGP Messages**
OPEN
UPDATE
KEEPALIVE
NOTIFICATION

**"Hot potato" routing**
Get this packet out of the router network as soon as possible, routing by quickest weight. 