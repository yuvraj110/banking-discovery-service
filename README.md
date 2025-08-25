# Discovery Server

## Description
Service registry for microservices. All services register here for discovery.

## Technologies
- Java 17
- Spring Boot
- Eureka Server
- Maven

## Features
- Service registration and discovery
- Helps API Gateway and other microservices locate each other

## Setup
- Annotate main class with `@EnableEurekaServer`
- Configure `application.yml` with service port and Eureka settings
