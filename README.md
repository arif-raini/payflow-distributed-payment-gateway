# 💳 PayFlow – Distributed Payment Gateway Platform

![Java](https://img.shields.io/badge/Java-21-blue)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-Microservices-brightgreen)
![Kafka](https://img.shields.io/badge/Kafka-Event--Driven-black)
![React](https://img.shields.io/badge/Frontend-React-blue)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)
![Redis](https://img.shields.io/badge/Cache-Redis-red)
![Docker](https://img.shields.io/badge/Deployment-Docker-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A **production-grade distributed payment gateway platform** inspired by **Razorpay and Stripe**, built using **Spring Boot Microservices, Kafka, Redis, PostgreSQL, and React**.

Designed as a **resume-grade backend engineering project** with real-world fintech architecture including **secure card vault tokenization, webhook retries, dead letter queue, merchant settlements, SAGA rollback, and circuit breakers**.

---

## 🚀 Features

- 🔐 JWT Authentication & Merchant Onboarding
- 💳 Payment Order Creation & Processing
- 🔁 Refund Management
- 🔐 AES-256 Card Vault Tokenization
- ⚡ Spring WebFlux Reactive APIs
- 📨 Kafka Event-Driven Architecture
- 🔄 Webhook Retry Mechanism
- 📦 Dead Letter Queue (DLQ)
- 🕛 Scheduled Merchant Settlements
- 🚦 Redis Rate Limiting
- 🛡 Resilience4j Circuit Breakers
- 🧾 Audit Logs
- 📊 Merchant Dashboard (React)
- 🐳 Dockerized Microservices
- 🔄 Idempotency Key Support
- 💼 SAGA Transaction Rollback

---

## 🏗 Architecture

```text
API Gateway
   |
   ├── Auth Service
   ├── Merchant Service
   ├── Payment Service
   ├── Card Vault Service
   ├── Webhook Service
   ├── Settlement Service
   ├── Notification Service
   └── Audit Log Service
```

## 📝 Daily Development Log

### 📅 Day 1 – Project Initialization
- Created GitHub repository
- Added professional microservices folder structure
- Added initial README and documentation folder
- Added backend, frontend, docs, scripts, and screenshots directories
- Initial commit pushed successfully

### 📅 Day 2 – Database Design
- To be updated