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
