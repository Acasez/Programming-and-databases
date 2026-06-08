### Overview
Entity Framework Core can be used used to connect [[Databases]] to [[ASP NET]]
Entity Framework was built on [[NET Core]], but is now separated from it since EF Core version 6 and onwards. The current version is EF Core 10, but many application/sites still use older versions as updating takes times. 

EFC is an ORM, an Object Relational Mapper, a library that implements the object-relational mapping technique. ORMs handles mapping between table formats and graphs.

ORM allows you work with classes/objects in code instead of having to write SQL against tables.
The written C# gets converted to SQL used on the table.

### EF 10
Entity Classes in [[C Sharp]]
dB Context as the central point for the databases and manages communication with the database.
dbSet for tables/collections
Fluent API and Data Annotations for model config
LINQ for queries
Migrations for creation and updating of databases
EF Core is directed connected to your code, less like a separate model like previous version
### Ways to work with Entity Framework
#### Database first
*Old model, possible but rarely used*
Manually creating a database
Then EF creates the classes
#### Code First
*Main method in use*
First we create our classes, then EF creates our databases from that
#### Model First
*Not supported since EF 6*
First we create a UML diagram and then EF creates a database and classes from it