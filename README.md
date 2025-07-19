# Spring Boot + Flask Microservices Communication Project (EC2 + Docker + Terraform)

🚀 Overview
This project demonstrates how two services, one written in Java (Spring Boot) and the other in Python (Flask), can communicate with each other over HTTP REST APIs, even though they're built in different languages.

It simulates a real-world microservices system where apps written in different tech stacks must work together.

🔧 What This Project Does
- Spring Boot service:

Built in Java

Exposes REST APIs (e.g., /api/hello)

Handles the core business logic

Flask service:

Built in Python

Sends requests to the Spring Boot APIs

Processes or uses the responses to do its own logic

Docker:

Both services run in separate Docker containers

Makes the environment consistent and portable

EC2 + Terraform:

We used Terraform to automatically deploy an Amazon EC2 instance

The EC2 server runs Docker containers for both services

This mirrors how microservices might be hosted in the cloud
