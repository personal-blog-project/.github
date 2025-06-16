# 📘 MSA Blog Platform

This is a microservices-based blog platform built with Spring Boot and React.  
Each service is isolated, independently deployable, and connected through Eureka + Gateway.

---

## 🧩 Services

| Service        | Description                      |
|----------------|----------------------------------|
| 🛡️ Auth Service | Handles login, registration, JWT |
| 👤 User Service | Manages user profiles            |
| 🌐 Gateway      | API entry point + security       |
| 📡 Eureka       | Service discovery registry       |
| 🖥️ Frontend     | React-based UI for the blog      |

---

## 🚀 Tech Stack

- Spring Boot 3.5.0
- Spring Cloud (Eureka, Gateway, Feign)
- Docker + GitHub Actions (CI/CD)

---

## 📊 System Architecture

![architecture](https://your-image-link.com/diagram.png)

---

## 📂 Repositories

각각의 마이크로서비스는 별도의 저장소로 관리됩니다.
