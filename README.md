# SpringBoot R2dbc Reactive APIs

## Tech Stack:
* Java 11
* Spring Boot
* Postgres
* Webflux
* r2dbc


## Requirements
* [Java 11](https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html)
* [Gradle](https://gradle.org/install/) 
* Editor of your choice (IntelliJ, STS or Eclipse), configure the editor with [lombok](https://projectlombok.org/setup/intellij) support.
* [Postgres Database](https://www.postgresql.org/download/macosx/)

## Reactive APIs:
* This microservice has reactive apis using Mono and Flux and connects to postgres database using r2dbc connection.
* SpringBoot library used for r2dbc is:
	```
		implementation 'org.springframework.boot:spring-boot-starter-data-r2dbc'
	```
* SpringBoot library used for reactive api is:
	```
		implementation 'org.springframework.boot:spring-boot-starter-webflux'
	```
	
# application.yml:
	```
	  r2dbc:
    	url: r2dbc:postgresql://localhost:5432/b008967
    	username: postgres
	```