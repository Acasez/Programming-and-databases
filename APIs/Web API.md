A web API is an [[API|application programming interface]] for [[Web Development]], typically for [[Dynamic Websites]]

A server-side web API consists of one or more publicly exposed [[Endpoints]] to a defined request–response message system, typically expressed in JSON or XML by means of an HTTP-based web server.*
## API Styles
### Minimal API
Minimal API's are simple tools that put the endpoints directly in the Program.cs class 

var builder = WebApplication.CreateBuilder(args);
var app = builder.Build();
app.MapGet("/hello", () => "Hej från Minimal API!");
app.MapGet("/hello/{name}", (string name) => $"Hej {name}!");
app.Run()
### Controller API
Controller APIs are the standard way of making API's. The endpoints are put in controller classes that can use models and other classes to interact with databases and code. 
They can provide a lot of structure to big projects
### Mixed API
You can also you both controller classes with endpoints and direct endpoints in the same API giving great amounts of flexibility.
### gRPC
https://en.wikipedia.org/wiki/GRPC
Remote Procedure Calls is specialized type of API that are useful for infernal service to service communication with high degrees of optimization. 
### SignalR
SignalR is used in realtime functions like chats, notifications and dashboards. 


