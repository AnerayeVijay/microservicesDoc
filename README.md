# Understanding mircoservices

## What are microservices? 
Robert C. Martin coined the term single responsibility principle which states “gather together those things that change for the same reason, and separate those things that change for different reasons.”

A microservices architecture takes this same approach and extends it to the loosely coupled services which can be developed, deployed, and maintained independently. Each of these services is responsible for discrete task and can communicate with other services through simple APIs to solve a larger complex business problem.

- Microservices are a software development technique that structures an application as a collection of loosely coupled services.
- In short, the microservice architectural style is an approach to developing a single application as a suite of small services, each running in its own process and communicating with lightweight mechanisms, often an HTTP resource API.
- In a microservices architecture, services are fine-grained and the protocols are lightweight.
- Microservices follow the principles of service-oriented architecture (SOA) design
  They are as follows:
    -  Standardized service contract (services follow a standardized description)
    -  Loose coupling (minimal dependencies)
    -  Service abstraction (services hide their internal logic)
    -  Service reusability (service structure is planned according to the DRY principle)
    -  Service autonomy (services internally control their own logic)
    -  Service statelessness (services don’t persist state from former requests)
   
- Microservices are most useful when you’re building for a more diverse consumer base

## Pros and Cons of microservices
### Pros
 - Easy Development:
 As the constituent services are small, they can be built by one or more small teams from the beginning separated by service boundaries which make it easier to scale up the development effort if need be
- Easy deployed :
  Once developed, these services can also be deployed independently
- Versatile :
Microservices allow for the use of different technologies and languages.
- Easy to integrate ans Scale with thirdpatry application
- Easy Maintenance is simpler and cheaper
-     Because each microservice can be developed and deployed independently, applications can be up and running quickly

### Cons
 - Increased effort for operations, deployment and monitoring.
 - Transaction safety. 
 - Decreased Performance:
 - Distributed deployment and process flows can create complicated testing
 - Increasing number of services can result in information barriers  The architecture brings additional complexity as the developers must
   implement fault tolerance, mitigate network latency, and deal with a variety of message formats as well as load balancing
 - In addition to several complexities of an existing monolithic architecture, the developers have to deal with the additional complexity
   of a distributed system
 - Handling use cases that span more than one service without using distributed transactions is not only tough but also requires  
   communication and cooperation between different teams
 - Partitioning the application into microservices is very much an art



## How to break a Monolith into Microservices
### Warm Up with a Simple and Fairly Decoupled Capability
### Minimize Dependency Back to the Monolith
### Decouple Vertically and Release the Data Early
### Split Sticky Capabilities Early
