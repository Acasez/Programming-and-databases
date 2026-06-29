### Clean Architecture
Core domain and use cases that is independent of frameworks and infrastructure
Can switch database structure without editing the core, designed to be framework agnostic
Prioritizes test ability and long term support.
Entities → Use Cases → Interface Adapters → Frameworks
### Onion Architecture
Similar to clean architecture, used with a lot of business logic. .
Emphasizes **domain models** and **interfaces**
Domain --> Application --> Infrastructure --> UI
### Vertical Slice Architecture
System is organized per feature or use case instead of layer. Every slice includes all the parts needed for that function.
Features are independent and very loosely coupled.
Might need the same code in multiple features, not DRY and hard to standardize. 
Good for prototypes. 
### Layered Architecture
System is split up into API/UI, service, domain and infrastructure..
Easy to setup and understand, good fit for small to middle sized APi's.
Can be hard to maintain for large projects
### Modular Monolith
Between layered and microservices. Singular project split into clear modules with clear borders.
Each module can have their own domain, application and infrastructure.
Often used by large [[Web API]]s 
### Hexagonal Architecture
Specialized architecture that focuses around a core that exposes ports that can be connected to. Similar to clean architecture. 
### Microservices
Style of architecture were the system is split into microservices that each handle their own part of the chain and communicate with each other. Used for large systems, complex to set up but easy to edit once set up.
Services become loosely coupled and can use different languages. 