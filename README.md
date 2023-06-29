# catarion_REST API 
### is a web-accessible API

    The RESTful API defines:
     - endpoints specification (URL)
     - HTTP methods (GET, POST, PUT, DELETE) that a client uses to interact with the server and perform operations on resources
     - data format (JSON)
     Work with relattional db (MySQL)
     Provide Authentication (User and Admin roles)

## What I learned
------ 

🧩 Implemented an API. Learned about **idempotent HTTP methods** (GET, PUT, ~~DELETE~~) and that a well-designed server should be idempotent!

🧩 Experienced with Relational Database (MySQL). Built relations between entities (Many-To-Many). Practiced lazy loading. Designed DTO object to solve **N+1 query problem** in ORM. Also I used JOIN FETCH to join 2 database tables (user & role) within the query and initialize the association on the returned entity. 

🧩 Provided Authentication (**Spring Security**) and provided Admin Panel and User Panel.

🧩 Designed the front end of the web app. Used HTML (page structure), CSS (style information), and JavaScript (behavior control of different elements). Additionally implemented jQuery (AJAX load() Method) and  Bootstrap (grid system) to simplify JavaScript coding. 

🧩 Explored Jackson library for **JSON processing** in Java (convert POJO objects to / from JSON).

🧩 Incorporated **Spring REST Client** - RestTemplate, as a primary tool for converting an object into a http-request and http-response into an object. Next project I plan to switch to an alternative HTTP client WebClient (that provides both synchronous and asynchronous approaches - no need to wait for http-response) as RestTemplate becomes depricated since Spring 5. In microservices - Feign Client (Spring Cloud).

### Screenshots 

DTO implementation in order to:
- deliver only the rerqiered data (instead of transferring the complete object)
- reflect what data is being transmitted
- reduction of connectivity between parts of code (client - server / service - controller)


Admin Panel 

User Panel

### Usage



