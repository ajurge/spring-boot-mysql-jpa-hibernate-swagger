## JPA + Hibernate + MySQL + Swagger with Spring Boot
RESTful web service demonstrating JPA, Hibernate, MySQL and Swagger usage with Spring Boot. API documentation is generated using Swagger.


### Instructions

Project should be built and run using Java 1.7 or above.

1. Open the `application.properties` file and set your own configurations for the
       database connection.
    
2. Build with Maven ```mvn clean install```  
    
3. Change directory to ```../spring-boot-mysql-jpa-hibernate-swagger/target/```
     
4. Execute in the terminal ```java -jar spring-boot-mysql-jpa-hibernate-swagger-1.0.0-SNAPSHOT.jar ``` 
    
Alternatively run ```mvn spring-boot:run``` from command line or IDE or execute *com.springboot.Application.main()* from within IDE.

Once the service is up and running the documentation of the REST API can be accessed at:
    
* API documentation JSON [http://localhost:8080/v2/api-docs/](http://localhost:8080/v2/api-docs)
* API documentation WEB UI [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)
