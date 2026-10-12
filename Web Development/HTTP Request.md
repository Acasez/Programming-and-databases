[[HTTP]] Requests are one type of HTTP messages sent to [[Web API]] [[Endpoints]]. HTTP Requests are often followed by a [[HTTP Response]]. [[Web Caches]] located closer to the client help speed up requests, leading to a quicker [[Round Trip Time|round trip time]].

| POST                  | GET                    | HEAD            | PUT                         |
| --------------------- | ---------------------- | --------------- | --------------------------- |
| Submit Data           | Retrieve Resource/Data | Retrieve Header | Uploads a new file          |
| Often from form input |                        |                 | Replaces file on the server |
Conditional GET, don't send request if browser has an up to data cached version. 


![[Pasted image 20260928092454.png]]