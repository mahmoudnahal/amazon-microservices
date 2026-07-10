# Amazon-Style E-Commerce Microservices

A microservices-based e-commerce system inspired by Amazon's architecture, built with Spring Boot. The system is composed of independent services that communicate directly with each other via REST APIs.

## 🏗️ Architecture

This project follows a microservices architecture with three independent services:

- **Product Service** — Manages product catalog and inventory
- **Order Service** — Handles order creation and processing
- **User Service** — Manages user accounts and authentication

Each service runs on its own port and communicates with other services directly via REST APIs (direct service-to-service communication).

## 🛠️ Built With

- Java / Spring Boot
- Docker
- GitHub Actions (CI/CD)
- REST APIs

## ✨ Features

- Independent, deployable microservices
- Dockerized services with containerization
- Automated CI/CD pipeline via GitHub Actions
- Service-to-service REST communication

## 🚀 Getting Started

1. Clone the repository
```bash
   git clone https://github.com/mahmoudnahal/amazon-microservices.git
```
2. Navigate to each service directory (`product-service`, `order-service`, `user-service`)
3. Build and run each service using Docker or your preferred Java build tool

## 📌 Roadmap

- [ ] Implement Saga Pattern for distributed transaction management across services
- [ ] Add API Gateway for unified request routing

## 👤 Author

Developed by [Mahmoud Al-Nahal](https://github.com/mahmoudnahal) as part of an Advanced Software Engineering project.
