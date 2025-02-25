### Spring Boot: 
Spring Boot is a Java framework that simplifies building stand-alone, production-ready Spring applications. It eliminates boilerplate code, provides embedded servers,
and follows convention over configuration, making development faster and easier.

### Standalone Application:
Applications that do not need to be deployed to an external server (eg Tomcat, Jetty).

# How are Spring Boot applications production-ready?

### Auto Configuration:

-> Spring Boot automatically configures necessary settings, such as database connections, caching, security, etc.</br>
-> You do not need to manually write many configurations.</br>

### Embedded Server:

-> Normally, an external server (like Apache Tomcat) is required to run Java web applications.</br>
-> Spring Boot comes with embedded Tomcat, Jetty, or Undertow, which can run applications directly without any extra setup.</br>

### Spring Boot Actuator (Monitoring & Health Check):
-> Actuator is a feature that provides real-time monitoring and health check APIs.</br>
-> If the app is about to crash or has an issue, alerts can be generated through the Actuator.</br>

### Logging & Debugging:

-> There is a built-in logging system that helps to easily track errors and issues.</br>
-> This is helpful for debugging and performance optimization in production.</br>

### Security Features:

-> Spring Boot has default security configurations that prevent unauthorized access.</br>
-> HTTPS support and authentication/authorization can be easily configured.</br>

### Containerization & Cloud Readiness:

-> Spring Boot applications can be easily deployed on Docker, Kubernetes and cloud platforms (AWS, GCP, Azure).</br>


### Example:
If you have built a simple web app and can deploy it directly on the server without any extra setup, then it is production-ready.</br>
Spring Boot simplifies this to achieve maximum efficiency with minimum effort.</br>

## Meaven: 
Maven is a tool that helps in managing libraries (dependencies) and building Java projects easily. In Spring Boot, it downloads required files automatically and helps in running, testing, and packaging the project with simple commands.

## Jar: 
A JAR (Java Archive) file is a compressed package that contains Java classes, resources, and libraries. It is used to distribute and run Java applications efficiently. Many third-party libraries (like Spring Boot) come in JAR format. You can run a JAR file using java -jar filename.jar.

## IOC: 
IOC (Inversion of Control) is a concept in Spring Boot where the framework takes control of object creation and dependency management instead of the developer. This allows Spring to automatically create and inject objects, reducing manual object creation. 

## ApplicationContext:
ApplicationContext is the implementation of Inversion of Control (IOC) in Spring Boot. It acts as a container that creates, manages, and injects beans (objects) automatically, following the IOC principle.

## Bean:
A Bean is an object that Spring creates and manages automatically.</br>
Note - Normal Object (Not a Bean)

## @SpringBootApplication:
@SpringBootApplication is a special annotation in Spring Boot that marks the main class of the application. It enables auto-configuration, component scanning, and configuration setup in a single step. It combines @EnableAutoConfiguration, @ComponentScan, and @Configuration to simplify Spring Boot setup.

## @ComponentScan: 
@ComponentScan tells Spring where to search for components like @Component, @Service, and @Repository. It automatically registers these beans in the Spring container for dependency injection.

## @AutoWired:
@Autowired is a Spring annotation that automatically injects dependencies (beans) without manual object creation. It helps in managing dependencies efficiently using Spring’s IOC container.

## @AutoConfiguration:
@AutoConfiguration in Spring Boot automatically configures beans based on the classpath and defined properties, reducing manual setup. It helps developers build applications with minimal configuration.

## @Configuration
@Configuration marks a class as a source of bean definitions for the Spring container.

## ORM: 
ORM (Object-Relational Mapping) is a technique that connects Java objects with database tables. In Spring Boot, Hibernate is commonly used for ORM to simplify database operations. It helps in managing data without writing complex SQL queries.

## @Document:
@Document is a Spring Data MongoDB annotation that marks a Java class as a MongoDB document. 

## @Id:
@Id is used to mark a field as the primary key, mapping it to MongoDB's _id field.

## Lombok:
Lombok is a Java library that helps reduce boilerplate code by automatically generating common methods like getters, setters, and constructors. It uses annotations to simplify code writing.

## @Bean:
In Spring Boot, @Bean is an annotation used on a method to define a Spring-managed bean. The method’s return value is registered in the Spring container, allowing manual object creation and dependency injection.

## Authentication:
Authentication is the process of verifying a user's identity to ensure they are who they claim to be. It typically involves credentials like a username and password, biometrics, or authentication tokens.

## Authorization:
Authorization decides what a user can access after their identity is verified. It controls permissions for actions and resources.
