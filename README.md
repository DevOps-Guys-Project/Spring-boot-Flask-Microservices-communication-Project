# Spring Boot + Flask Microservices Communication Project (EC2 + Docker + Terraform)

## 🚀 Overview
This is a simple backend-only project that shows how two services, one written in Java (Spring Boot) and the other in Python (Flask), can communicate with each other using REST APIs.

There is no frontend. The focus is on how two backend services in different programming languages can work together.

&nbsp;

🔧 **What This Project Does**
&nbsp;
- **Spring Boot service (Built in Java)**:  
  - Exposes REST API endpoints
  - Handles some core logic and returns responses  

&nbsp;

- **Flask service (Built in Python)**:  
  - Sends HTTP requests to the Spring Boot service
  - Processes the response and applies its own logic

&nbsp;

**Docker:**
  - Each service runs in its own container
  - Ensures consistency across development and deployment

&nbsp;

**EC2 + Terraform:**
  - An AWS EC2 instance is created using Terraform
  - Both Docker containers are deployed and run on that EC2 instance
