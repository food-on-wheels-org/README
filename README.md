# food-on-wheels-app
## Overview
This project is a full-stack food delivery application that simulates food delivery with features like  restaurant listing, restaurant registration, user sign-up and much more. This is being developed as part of a learning curriculum based on multiple Udemy courses, with enhancements and customizations added along the way.

## Tech Stack:
- Java Spring Boot (Microservices architecture)
- Eureka Discovery
- JUnit
- Angular (Frontend)
- MySQL (Database)
- Docker and Kubernetes (for containerization)
- Jenkins (Pipeline setup)
- Sonar (code evaluation)
- Argo CD (CI/CD setup)
- AWS EKS
- AWS ALB
- AWS EC2
- AWS RDS
- Mongo Atlas
- Lombok
- Mapstruct

---

## Architecture
The backend is designed using a microservices architecture, including the following services:

| Service              | Description                                |
|----------------------|--------------------------------------------|
| eureka	       | Eureka service registry                    |
| restaurant-listing   | Restaurant information 		    |
| menu-directory       | All menus			            |
| user-details         | User accounts and profiles         	    |
| order-service        | Cart, orders, and checkout         	    |
| payment-service      | Dummy payment simulation                   |

The frontend (Angular) consumes REST APIs exposed by the gateway.

---

## Setup Instructions

### Prerequisites
- Java 17+
- Node.js + Angular CLI
- Docker
- MySQL
- AWS

### Steps to Run Locally
1. Clone the repo  
   ```bash
   https://github.com/TejasSrivathsa/food-on-wheels-app.git
   cd food-delivery-app
   ```

2. Start required containers using Docker Compose:
   ```bash
   docker-compose up -d
   ```

3. Run each microservice manually or via IntelliJ.

4. Start Angular frontend:
   ```bash
   cd frontend
   npm install
   ng serve
   ```

5. Open browser at `http://localhost:4200/`

---

## Folder Structure
```
/eureka
/user-details
/order-service
/restaurant-listing
```

---

## Features (Work in Progress)

- User Signup/Login  
- Restaurant Listing  
- Cart Management   
- Admin Restaurant Portal  
- Payment Simulation  

---

## Learning Goals

This project is part of a hands-on learning journey, aiming to:
- Understand microservices design patterns
- Implement event-driven architecture using Kafka
- Practice DevOps fundamentals (Docker, CI/CD)
- Strengthen frontend-backend integration using Angular and REST APIs


---

## Author

Tejas Srivathsa  
Connect on [LinkedIn](https://www.linkedin.com/in/tejas-s-405237169/)  

---

## License
This project is for educational purposes only.
