## MICROSERVICES ARCHITECTURE

### What is Microservices Architecture?

Microservices Architecture is a software development technique. It is a service oriented architecture (SOA) architectural style that structures an application as a collection of services that are 
*	Highly maintainable and testable using HTTP.
*	Loosely coupled-means dependency between modules is very low.
*	Independent deployable.
*	Organized around business capabilities.
*	Owned by a small team.
It enables rapid, frequent and reliable delivery of large complex applications and also enables an organization to evolve its technology stack. In Microservices Architecture, services are fine grained and protocols are lightweight.

### Difference between Microservices and Monolithic Architecture:

*	Microservices Architecture is built as a suit of small services each with their own code base whereas Monolithic Architecture is built as one large system and is usually on code base.
*	Microservices Architecture is independent deployable however monolithic Architecture is often deployed all at once, regardless of what was changed in code.

### Advantages:

*	Modularity: This makes the application easier to understand, develop, test, and become more resilient to architecture erosion.
*	Scalability: Since microservices are implemented and deployed independently of each other.
*	Distributed development: It parallelizes development by enabling small autonomous teams to develop, deploy and scale their respective services independently.

### Diadvantages:

*	Distributed System: By the fact that Microservices Architecture is a distributed system it adds complexities to the project.
*	Testing a microservices application is also much more complex than in case of monolithic web application.
*	It is more difficult to implement changes that span multiple services because in microservices Architecture you need to carefully plan and coordinate the rollout of changes to each of the services. 
*	Deploying a microservices based application is also more complex because microservices application typically consists of a large number of services and each service will have multiple runtime instances.

### Conclusion:

Microservices Architecture pattern is the better choice for complex, evolving applications. Actually the microservices approach is all about handling a complex system, but in order to do so the approach introduces its own set of complexities and implementation challenges.

