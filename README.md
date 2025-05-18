# Kafka Streams Playground

A full-stack Kafka messaging playground with a modular architecture.

This repository combines:

- ✅ **Spring Boot Kafka Backend** (Producer/Publisher)
- ✅ **Angular Frontend App** (Standalone components using SCSS)
- ✅ **Shared Interface Definitions** (Optional module for DTOs or models)

---

## 📦 Repository Structure

| Folder                  | Description                                           |
|--------------------------|-------------------------------------------------------|
| `spring-kafka-service`   | Spring Boot application for Kafka message handling   |
| `angular-kafka-app`      | Angular application for sending Kafka messages       |
| `kafka-message`          | Shared models/interfaces between frontend and backend (optional)

---

## 🚀 Getting Started

### 🔁 Clone with Submodules

```bash
git clone --recurse-submodules https://github.com/VinayakGawade0/kafka-streams.git
```

#### If already cloned:
```
git submodule update --init --recursive
```

🧩 Add Submodules (if needed manually)
```
git submodule add https://github.com/VinayakGawade0/kafka-message.git kafka-message
git submodule add https://github.com/VinayakGawade0/spring-kafka-service.git spring-kafka-service
git submodule add https://github.com/VinayakGawade0/angular-kafka-app.git angular-kafka-app
```


### 🛠️ Prerequisites

✅ Apache Kafka & Zookeeper running on localhost:9092

✅ Java 17+ (for Spring Boot backend)

✅ Node.js (v18+) and Angular CLI (v17+) for frontend

### 🔐 CORS Enabled
The backend is configured with CORS to allow communication with the Angular frontend during development.

MIT License @ Vinayak Gawade
