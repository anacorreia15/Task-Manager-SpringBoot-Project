# Task Manager - SpringBoot Project
### 🎯 General Objective
Develop a backend application based on microservices for the management of personal tasks (To-Do List), focusing on good development practices, security, modularity and scalability, using Java and Spring Boot.

The system should allow users to register, log in, and create, consult, edit and delete tasks. The project will consist of multiple autonomous services that communicate with each other, through a distributed architecture.
### 🧩 Expected Architecture
The system will consist of four main microservices:
1. user-service – User management and authentication via JWT.
2. task-service – Task management (CRUD), associated with an authenticated user.
3. api-gateway – Central routing of all calls to the microservices.
4. discovery-service (optional) – Service registration and discovery (Eureka).
### 🔐 Key features
Authentication and Authorization (user-service):
- POST /auth/register – Register user
- Copyright © 2019 JWT. All Rights Reserved.
- GET /users/me – Authenticated profile
Task Management:
- POST /tasks – Create task
- GET /tasks – List task
- PUT /tasks/{id} – Update task
- DELETE /tasks/{id} – Delete task
  
⚠️ All routes in the task-service must be protected by JWT authentication via API Gateway.
### 🧱 Mandatory Technologies
- Java 17 or latest
- Spring Boot
- Spring Security + JWT
- Spring Data JPA
- PostgreSQL or H2
- Spring Cloud Gateway
- Git e GitHub
- Swagger/OpenAPI- (Opcional)
- Eureka- (Opcional) Docker e Docker Compose
  
### ✅ Technical Requirements
- Clear separation by layers: Controller, Service, Repository, DTO, Entity
- Validation with @Valid and exception handling with @ControllerAdvice
- Use of DTOs for secure data exposure
- Automatically generated Swagger documentation
- Clean, modular and well-structured code
- Git with clear and descriptive commit history
  
### 🧪 Bonuses (not mandatory, but recommended)
- Unit tests with JUnit
- Docker Compose for orchestration
- CI/CD with GitHub Actions
- Additional microservice of notifications (logs, email, etc.)
  
### 📦 Delivery
Project published on GitHub with explanatory README.md containing: 
  - Introduction to the project
  - Instructions for execution
  - Technologies used
  - Screenshots (Swagger, Postman, etc.)
    
### 💡 Ultimate Goal
This project will serve as a portfolio to demonstrate technical capability in Java, microservices, and Spring Boot, and can be used in interviews, applications, or proofs of concept.
