https://en.wikipedia.org/wiki/JSON_Web_Token

There are many ways to set up security. identity, and authorization in [[Web Development]]. 

## JWT
[[JWT]] or JSON Web Token are often used.  
Scales well, best for microservices
Hard to revoke, payload is visible
## Session Cookie
Server creates a session on login- They are easy to create and revoke, but don't scale well across services whiteout a shared store. Best for traditional web apps with a single 
backend.
## OAuth 2.0
Login via an authorization server.
Allows for "Login with Google" and similar. 
Complex to implement
## API Keys
Static long lived, tied to service or developer account. 
No user identity, no expiry by default, leaked keys are dangerous

| Type     | Implementation | Scaling | State     | User Identity | Best For                |
| -------- | -------------- | ------- | --------- | ------------- | ----------------------- |
| Session  | Easy           | Bad     | Stateful  | Yes           | Web app, single backend |
| JWT      | Medium         | Good    | Stateless | Yes           | Microservices, mobile   |
| Oath 2.0 | Complex        | Good    | Mixed     | Yes           | Third Party Access      |
| API KEys | Medium         | Good    | Stateful  | No            | Server to Server        |
|          |                |         |           |               |                         |

![[Pasted image 20260624105306.png]]