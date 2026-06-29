[[API]] versioning is done to able to continue improve on it without breaking clients using it. 

Unlike normal code which the client can choose to update when it fits them, public facing APi's are already used in production for the users and refactoring them may break things for the clients. 

[[Web API]]s  needs to support different versions at a time to let their users update their code over time. 
## Web APIs versioning strategies
### URL Versioning
URL versioning is the most common type
/api/v1/products
/api/v2/products
### Query String
Query string is easy to implement, but less clear to the user.
api/products?version=1
### Header-Versioning
Clearner URLs but harder to implement
GET /api/products
api-version: 1
