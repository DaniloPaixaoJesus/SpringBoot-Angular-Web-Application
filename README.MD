## Considerations about some architectural decisions::

SpringBoot -> java framework with the Convention over Configuration philosophy. Facilitates the configuration of the application and execution in the DEV environment since this one brings an embedded server.

Liquibase -> Keeps history of all changes to the database structure. Facilitates rollback of releases, facility to generate load script.

LomBok ->  excellent for abstracting some design patterns, as well as speeding up the development and writing of code.

Swwager -> framework for REST API documentation.

Angular 6 with Material Design -> Speed in the development of screens and user interface


## Prerequisites for Java Dev ##
Node 8, Angular Cli 6, Maven, JDK Java 8, Docker, Docker-Compose, Lombok

## Prerequisites for Deploy and Build ## 
Docker, Docker-Compose

## Step by step for Deploy ## 
Install Docker
Instaall Docker-compose
Clone project
run on root project: docker-compose up --build -d
Access:
http://localhost -> App
http://localhost:8080/swagger-ui.html -> API
