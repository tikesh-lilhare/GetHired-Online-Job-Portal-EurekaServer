## GetHired - Online Job Portal / Eureka Server

📌 Overview

The Eureka Server is the Service Discovery component of the AI-Powered Job Portal Microservices Architecture. It acts as a centralized registry where all microservices register themselves and discover other available services dynamically.Instead of communicating through fixed IP addresses or ports, services locate each other using their registered service names. This makes the system highly scalable, fault tolerant, and easier to maintain.The Eureka Server continuously monitors the health of all registered services through heartbeat mechanisms and automatically removes unavailable services from the registry.

---

## 🏗 Microservice Architecture

<img width="1536" height="1024" alt="ChatGPT Image Jul 3, 2026, 09_34_28 PM" src="https://github.com/user-attachments/assets/3e7f2fc6-8388-4f18-86e9-25a8452183f1" />


---

## 🛠 Tech Stack
## Backend
- Java 21
- Spring Boot
- Spring Cloud Netflix Eureka Server
- Maven

---

## 📦 Maven Dependencies
The project uses the following dependencies:

- Spring Boot Starter Web
- Spring Cloud Netflix Eureka Server
- Spring Boot Starter Actuator
- Spring Boot Starter Test
- Lombok

---

## 📁 Project Structure


---

## 📡 Registered Services

The following microservices register themselves with Eureka Server:
- API Gateway
- User Service
- Job Service
- Application Service

---

## ▶ Running the Server

## Clone Repository
git clone https://github.com/yourusername/eureka-server.git

## Move into Project
cd eureka-server

## Build Project
mvn clean install

## Run Application
mvn spring-boot:run

