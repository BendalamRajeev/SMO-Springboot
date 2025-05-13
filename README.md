# 🧵📊 Sewing Machine Operator (SMO) – Spring Boot Backend

> 💡 A robust Spring Boot backend for tracking and optimizing worker and sewing machine performance in the garment industry. This backend powers the SMO Android App.

![Java](https://img.shields.io/badge/Java-17-blue?logo=java)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.0-green?logo=spring)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange?logo=mysql)
![Build](https://img.shields.io/badge/Build-Maven-brightgreen?logo=apache-maven)
![License](https://img.shields.io/github/license/BendalamRajeev/smo-backend)

---

## 📦 Overview

The **SMO Backend** is a Spring Boot application that supports the Android-based **Sewing Machine Optimization System**. It enables factory floor digitization by managing:

- 👷 Worker performance data
- 🪡 Sewing machine efficiency
- ⏱️ Downtime & idle time
- 📊 Productivity statistics

All data is managed securely via RESTful APIs and stored in a MySQL database.

---

## ✨ Features

✅ **Worker & Machine Management**  
✅ **RESTful API for Android Integration**  
✅ **MySQL + Spring Data JPA**  
✅ **Authentication with Spring Security**  
✅ **Lombok to reduce boilerplate**  
✅ **Supports offline data syncing**  

---

## 🔧 Tech Stack

| Tech          | Purpose                            |
|---------------|------------------------------------|
| ☕ Java 17     | Backend language                   |
| 🌱 Spring Boot| Main framework                     |
| 🛡️ Spring Security | API authentication           |
| 📦 Spring Data JPA | Database ORM layer            |
| 🐬 MySQL       | Relational database                |
| 🛠️ Maven       | Project build tool                |
| 🔁 Lombok      | Reduces boilerplate in models      |

---
## 🚀 Getting Started

### ✅ Prerequisites

- Java 17+
- MySQL 8+
- Maven

### 📥 Clone & Run

```bash
git clone https://github.com/BendalamRajeev/smo-backend.git
cd smo-backend
./mvnw spring-boot:run
```
---
📲 Android Integration
The backend is fully compatible with the SMO Android App. It enables:

📈 Daily performance tracking

📤 Upload of machine/worker logs

🔄 Offline-first sync support

