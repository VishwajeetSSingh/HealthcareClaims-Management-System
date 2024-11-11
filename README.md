# Claims Management System

### It contains following features:
1.  **Member Microservice** - An authorized member can view premium bills, submit the claim, can view the claim status, which is already submitted. 
2.  **Claims Microservice** - Member Microservice interacts with Claims Microservice. It will give the status of submitted claim.
3.  **Policy Microservice** - To verify claim eligibility, claims microservice will interact with Policy Microservice which provides the permissible providers in which healthcare services can be offered.
4.  **Authorization Microservice** - This service authenticate already registered users and hence provides security to the system.
5.  **Member portal** - This is a frontend application that uses all microservices. 


## Use Case Diagram:
![456](https://user-images.githubusercontent.com/62255672/148811747-50af54f1-8209-488c-99ec-14753b7ab7ef.PNG)

## System Architecture Diagram
![123](https://user-images.githubusercontent.com/62255672/148811743-34333e8d-4237-4951-bdfe-c21587950b09.PNG)


## Skills used:
- **Java 8 Features**
- **Spring Boot**
- **Microservices and RestFul API**
- **Spring Data JPA**
- **Spring Cloud** - API gateway, Load Balancing, Service Discovery using Eureka, Config Server, Feign Client, Fault Tolerance, and many more Spring cloud features.
- **Spring Security** - Spring Security, JWT Authentication, and many more features of Spring security.
- **Docker and Kuberneter**
- **Amazon Web Services (AWS)**
- **Swagger Documentation**
