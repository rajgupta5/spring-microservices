# spring-microservices

### Introduction

Why Spring? [https://spring.io/why-spring]

Developing RESTful web services is fun. The combination of Spring Boot, Spring Web MVC, Spring Web Services and JPA makes it even more fun. And its even more fun to create Microservices.

There are two parts to this course - RESTful web services and Microservices

Architectures are moving towards microservices. 

RESTful web services are the first step to developing great microservices. Spring Boot, in combination with Spring Web MVC (also called Spring REST) makes it easy to develop RESTful web services. 

In the first part of the course, you will learn the basics of RESTful web services developing resources for a social media application. You will learn to implement these resources with multiple features - versioning, exception handling, documentation (Swagger), basic authentication (Spring Security), filtering and HATEOAS. You will learn the best practices in designing RESTful web services.

In this part of the course, you will be using Spring (Dependency Management), Spring MVC (or Spring REST), Spring Boot, Spring Security (Authentication and Authorization), Spring Boot Actuator (Monitoring), Swagger (Documentation), Maven (dependencies management), Eclipse (IDE), Postman (REST Services Client) and Tomcat Embedded Web Server. We will help you set up each one of these.

In the second part of the course, you will learn the basics of Microservices. You will understand how to implement microservices using Spring Cloud.

In this part of the course, you will learn to establish communication between microservices, enable load balancing, scaling up and down of microservices. You will also learn to centralize configuration of microservices with Spring Cloud Config Server. You will implement Eureka Naming Server and Distributed tracing with Spring Cloud Sleuth and Zipkin. You will create fault toleranct microservices with Zipkin

Spring reduces the complexity of enterprise java applications. Incredibly modular architecture of spring helps in picking and choosing the right spring modules to use to suit our needs. Spring reduces the cost of programming to interfaces to almost zero.

### Why is Spring Popular?

Wlets look at few of the things Spring helps with. 

Spring is one of the first layer independent frameworks.

Unit Testing builds up Loose Coupling. Architecture Flexibility is a result of Spring Modules.

- Dependency Injection
- Loose Coupling
- Spring Modules
- Architectural Flexibility - Great integration with other frameworks and helps us pick and choose the right ones.
- Unit Testing


### Basic Concepts
- Component
- Service
- Component Scan
- Autowiring

### Advanced Concepts
- Application Context
- Bean Factory
- Bean Scope
- Constructor Setter Injection
- Debugging 

### Spring Modules
- MVC
- JDBC
- AOP
- Test
- XML

![Spring Framework](https://docs.spring.io/spring-framework/docs/3.0.x/spring-framework-reference/html/images/spring-overview.png)


### Spring Boot Introduction
Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can “just run”. Most Spring Boot applications need very little Spring configuration.

With Microservices, focus is shifting to getting started with developing web applications quickly. Spring Boot enables this.

### Spring Framework in 10 steps
[https://github.com/in28minutes/spring-web-services/tree/master/spring-in-10-steps]


1. Setup a spring project using http://start.spring.io
2. Understand Tight Coupling using BinarySearchAlgorithm example
3. Make BinarySearchAlgorithm example loosly coupled
4. Using Spring to manage dependencies - @Component, @Autowired
  - @Component is used for declaring the bean
  - @Autowired is used for declraing dependency
5. Whats happening in background
  - Component Scan
  - Identification of candidate component classes
  - Creation of beans
  - Autowiring
6. Dynamic Autowiring using @Primary
7. Constructor and Setter Injection
  - All mandatory dependencies should be resolved using Constructor Injection
  - By Default Autowired means Setter Injection if there is no constructor defined
8. Spring Modules
9. Spring Projects
  - Spring Boot - Quickly build applications
  - Spring Cloud - Build Cloud native apps
  - Spring Data - Consistent Data Access
  - Spring Integration - Application Integration
  - Spring Batch - Batch Applications
  - Spring Security - Protect your applications
  - Spring HATEOAS - HATEOAS compatible services
  - Others - Spring Mobile, Spring Session, Spring Web Services, Spring for Android etc.
10. Why is spring so popular?


### Spring Boot in 10 steps
[https://github.com/in28minutes/spring-web-services/tree/master/springboot-in-10-steps]

- Step 1 : Introduction to Spring Boot - Goals and Important Features
- Step 2 : Developing Spring Applications before Spring Boot
- Step 3 : Using Spring Initializr to create a Spring Boot Application
- Step 4 : Creating a Simple REST Controller
- Step 5 : What is Spring Boot Auto Configuration?
  - To see the logs set 'logging.level.org.springframework = debug' in application.properties
- Step 6 : Spring Boot vs Spring vs Spring MVC
- Step 7 : Spring Boot Starter Projects - Starter Web and Starter JPA
- Step 8 : Overview of different Spring Boot Starter Projects
- Step 9 : Spring Boot Actuator
- Step 10 : Spring Boot Developer Tools

### References
- https://github.com/in28minutes
