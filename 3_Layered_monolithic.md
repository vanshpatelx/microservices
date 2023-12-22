Problem: Code Become Too Complex Over Time

Problems
1. Become Complex over time
2. Hard to Understand Codes
3. Need Code Organization

Solutions
1. Separate UI, Business and Data Layers as logical layers
3. Layered Architecture
4. SOLID Design


Components of a Layered Architecture
1. Presentation Layer
-> Responsible for user interactions with the software system, for example, a web app.
2. Application/Business Layer
-> Handles aspects related to accomplishing functional requirements including use case implementations.
3. Database Layer
-> Responsible for handling data, databases, such as a SQL database.


***Design principles - Separation of Concerns (SoC)***
1. separating a computer program into distinct sections
2. Isolate the software application into separate sections, manages complexity by partitioning the software system
3. Distinguish between the concepts of layer and tiers with certain responsibilities.
4. Elements in the software should be unique
5. Limits to allocate responsibilities
6. Low-coupling, high-cohesion

***Design principles - SOLID***
1. Single Responsibility
-> Each of your components or modules should responsible only one functionality.
2. Open-Closed Principle
-> When we design the system, it should able to extend without changing existing architecture.
3. Liskov Substitution Principle
-> Systems can be substitute each other easily. In our case we can use plug-in services that we can shift them easily.
4. Interface Segregation Principle
-> States that no code should be forced to depend on methods it doesn't use.
5. Dependency Inversion Principle
-> States that high-level modules should not depend on low-level modules; both should depend on abstractions 






Benefits
1. Easy Development, Debug and Deploy
2. Horizontal Logical Layers
3. Separation of Concerns

Drawbacks
1. Layers Dependent each other
2. Highly Coupling
3. Hard to maintanance
4. Complexity of codebase
5. Hard to Change libraries:  i.e. Change orm tool with different library Requires to modify business layer