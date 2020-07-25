# Spring Admin Dashboard

A Spring Boot multi module Project for monitoring spring boot applications


### Requirements :
- JDK >= 1.8 
- Please make sure you set $JAVA_HOME points to the correct JDK 

### Build :
Install the dependencies and devDependencies and start the Application.

```sh
git clone https://github.com/karthikeyan-thiyagarajan/spring-admin.git
$ cd spring-admin    
$ mvn clean compile                         ## To compile
$ mvn spring-boot:run -pl server-module     ## To Run the Server : 
mvn spring-boot:run -pl cilent-module-1     ## To Run the Client 1 :
mvn spring-boot:run -pl cilent-module-2     ## To Run the Client 2 :

```
and Go to the Browser : Dashboard (http://localhost:8181/)