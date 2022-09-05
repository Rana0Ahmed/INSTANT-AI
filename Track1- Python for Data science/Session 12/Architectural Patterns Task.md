# Architectural patterns
### - An architectural pattern is a general, reusable solution to a commonly occurring problem in software architecture.
### - It serves as a blueprint for the software systems.

## Different Software Architecture Patterns :
 - Layered Pattern
 - Client-Server Pattern
 - Event-Driven Pattern
 - Microkernel Pattern
 - Microservices Pattern
 
## 1. Layered Pattern :
- In Layerd pattern, components(code) are separated into layers of subtasks and they are arranged one above another.  
- Each layer has unique tasks to do and all the layers are independent of one another, one can modify the code inside a layer without affecting others.
- This layer is also known as `N-tier architecture`.
- Basically, this pattern has 4 layers :
  - Presentation layer (The user interface layer where we see and enter data into an application.)
  - Business layer (this layer is responsible for executing business logic as per the request.)
  - Application layer (this layer acts as a medium for communication between the ‘presentation layer’ and ‘data layer’.
  - Data layer (this layer has a database for managing data.)
  
## 2. Client-Server Pattern :
 - This pattern has two major entities, server and multiple clients.  
 - Here the server has resources(data, files or services) and a client requests the server for a particular resource. Then the server processes the request and responds back accordingly.
 - Examples of software developed in this pattern:  
   - Email.
   - WWW .
   - File sharing apps.
   - Banking, etc…
   
## 3. Event-Driven Pattern :
  -  This pattern is an agile approach in which services of the software are triggered by events.     
  - `(Event) When a user takes action in the application built using the EDA approach, a state change happens and a reaction is generated that is called an event`.
  - This pattern is used for building websites with JavaScript and e-commerce websites in general.  
  
## 4. Microkernel Pattern :
 - This pattern has two major components, a core system and plug-in modules. 
 - `Core system handles the fundamental and minimal operations of the application`.
 - `Plug-in modules handle the extended functionalities (like extra features) and customized processing`.
 - This pattern is used for :
   - Product-based applications and scheduling applications.
   
## 5. Microservices Pattern :
 - The concept of microservices pattern is the collection of small services that are combined to form the actual application.
 - Small programs are built for every service (function) of an application independently, those small programs are bundled together to be a full-fledged application (instead of building a bigger application).
 - When an application is built in a microservices pattern, adding new features and modifying existing microservices without affecting other microservices are a challenge.
 - This pattern is most suitable for websites and web apps having small components EX:
   - Netflix

