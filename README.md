# sprintboot-tryout
Trying out spring boot for API development

* The customizability of application properties is in the application.properties file
* And the list of what all can be customized is listed in spring boot documentation

* ORMs essentially map your classes to database tables
* Entities here are these objects that are created to be mapped as a table

* JPA repository is where the SQL magic happens

* @RequestBody converts the JSON object that is passed in to the object of desire

* @Autowired wires an object automatically to an object
* H-2 is in memory database

* Service layers contain business logic like validation and some changes before interacting with the repository

* Lombok removes boilerplate code for getter setters etc

* Tests were created using Mockito and JUnit. 

* Mockito allows to create a "mock" entity and not mess with real objects/data
* Java bean is a standard for classes
* Actuator help to add some endpoints to monitor the health of the application