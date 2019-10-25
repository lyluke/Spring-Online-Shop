# Spring-Online-Shop

## Business Design
  - Designed a web application based on Spring MVC to support item search and listing for online shops.

## General Instruction
1.	Applied the concept of **dependency injection** and inversion of control in the process of code design.
2.	Utilized **Hibernate** with object-relational mapping to provide effortless support of database operations.
3. 	Developed a Spring Web Flow(**MVC**) with view, action and end statuses to support item ordering.

## Infrastructure Design
### Hibernate Interfaces
  - SessionFactory: SessionFactory is an immutable thread-safe cache of compiled mappings for a single database. We need to initialize SessionFactory once and then we can cache and reuse it. SessionFactory instance is used to get the Session objects for database operations.
  - Session: Session is a single-threaded, short-lived object representing a conversation between the application and the persistent store. Session object is the interface between java application code and hibernate framework and provide methods for CRUD operations.
  - Transaction: Transaction is a single-threaded, short-lived object used by the application to specify atomic units of work.
  
  <p align="center"> 
    <img src="https://github.com/lyluke/Spring-Online-Shop/blob/master/res/Hibernate.jpg" width="700">
  </p>
  
### The Benefits of Using Spring
  - **Lightweight**: there is a slight overhead of using the framework in development
  - **Inversion** of Control (IoC): Spring container takes care of wiring dependencies of various objects, instead of creating or looking for dependent objects
  - **IoC container**: it manages Spring Bean life cycle and project specific configurations
  - **Spring is non invasive**: That means you no need to implements any interface or inherit any class from spring to your classes, so whenever you want to change from spring to any other technology then you no need to change the logics of your class.
  - **End to end Development**: Spring supports all aspects of application development, Web aspects, Business aspects, Persistence aspects, etc, so we can develop a complete application using spring.
  <p align="center"> 
    <img src="https://github.com/lyluke/Spring-Online-Shop/blob/master/res/Reverse_Control.png" width="500">
  </p>
  
### Spring Web Flow
  - Spring is the most broadly used framework for the development of Java Enterprise Edition applications.
  - JavaEE is a set of specifications, extending Java SE with specifications for enterprise features such as distributed computing and web services.
  <p align="center"> 
    <img src="https://github.com/lyluke/Spring-Online-Shop/blob/master/res/Spring_MVC.png" width="500" alt="Spring MVC">
  </p>

  


