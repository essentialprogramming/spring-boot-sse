# Spring Boot SSE Server
This is an example of how to implement a SSE server in Spring Boot.

## Build
mvn install

## Local run from IDEA
* Open Edit Configuration -> add Application
* Add main class: com.sse.Application
* Working directory: <path>\spring-boot-sse
* Use classpath of module: spring-boot-sse
* JRE: 1.8

## Local run jar
java -jar target/spring-boot-sse-1.0.0-SNAPSHOT.jar

Open localhost:8080/index.html in your browser to see the events sent from server.