# 🛒 Microservices-Based E-Commerce Platform

A **scalable, event-driven e-commerce system** built using a microservices architecture.
Each service is independently deployable and communicates through REST APIs and asynchronous messaging.
The project demonstrates **modular design, inter-service communication, and real-world system scalability principles**.

#### Product Catalog Service : https://github.com/deepakChourasiya-aj/ProductCatalogService
#### Auth Service : https://github.com/deepakChourasiya-aj/UserAuthService
#### Communication/Notification Service : https://github.com/deepakChourasiya-aj/CommunicationService
#### Payment Service : https://github.com/deepakChourasiya-aj/PaymentService

---

## ⚙️ Architecture Overview

The platform consists of multiple microservices, each responsible for a distinct business function:

| Service                        | Description                                                              | Repository                                                                              |
| ------------------------------ | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------- |
| 🧾 **Product Catalog Service** | Handles product listing, filtering, and inventory management.            | [Product Catalog Service](https://github.com/deepakChourasiya-aj/ProductCatalogService) |
| 🔐 **Authentication Service**  | Manages user registration, login, and JWT-based authentication.          | [Auth Service](https://github.com/deepakChourasiya-aj/UserAuthService)                  |
| ✉️ **Notification Service**    | Sends real-time notifications via email/SMS using Kafka events.          | [Communication Service](https://github.com/deepakChourasiya-aj/CommunicationService)    |
| 💳 **Payment Service**         | Integrates payment gateways like Razorpay and Stripe for order payments. | [Payment Service](https://github.com/deepakChourasiya-aj/PaymentService)                |

---

## 🚀 Tech Stack

**Backend:** Java, Spring Boot, Spring Cloud, Hibernate, JPA
**Database:** MySQL
**Messaging Queue:** Apache Kafka
**Caching:** Redis
**API Gateway & Discovery:** Spring Cloud Gateway, Eureka
**Payment Integration:** Razorpay, Stripe
**Build & Deployment:** Docker, AWS, CI/CD (GitHub Actions)

---

## 🧩 Key Features

* **Microservices Architecture** — loosely coupled, independently deployable services.
* **Service Discovery & Gateway** — Eureka and Spring Cloud Gateway for dynamic routing.
* **Event-Driven Communication** — Kafka for asynchronous inter-service messaging.
* **Secure Authentication** — JWT-based authentication for all services.
* **Payment Integration** — Seamless payment flow using Razorpay and Stripe APIs.
* **Caching Layer** — Redis to optimize frequently accessed data and reduce latency.
* **Scalability** — Containerized with Docker and deployed on AWS.
* **CI/CD Pipeline** — Automated builds and deployments using GitHub Actions.

---

## 📊 Performance Highlights

* Reduced average API response time from **~500 ms to ~20 ms** using Redis caching.
* Kafka-based messaging system achieved **6k+ messages/sec throughput** in load testing.
* Supports **horizontal scaling** for high-traffic scenarios.

---

## 🧪 Setup Instructions

1. Clone individual service repositories (links above).
2. Start **Eureka Server** and **API Gateway**.
3. Configure `.env` or `application.yml` files for DB, Redis, and Kafka.
4. Build each service using Maven/Gradle.
5. Run using Docker or directly via `java -jar`.

---

## 👨‍💻 Author

**Deepak Chourasiya**
Backend Engineer | Java | Spring Boot | Microservices | Kafka | AWS
[LinkedIn](https://www.linkedin.com/in/deepak-aj/) • [GitHub](https://github.com/deepakChourasiya-aj)

