# Admin Server (Spring Boot Admin)

## 📌 Project Overview

This project demonstrates the implementation of **Spring Boot Admin Server** for monitoring and managing Spring Boot applications in a **Microservices Architecture**.

The Admin Server provides a centralized dashboard to monitor the health, status, metrics, environment, beans, logs, and other actuator endpoints of registered microservices.

---

## 🚀 Features

* Spring Boot Admin Server
* Centralized Monitoring Dashboard
* Application Health Monitoring
* Live Status Monitoring
* Metrics Monitoring
* Environment Information
* Log Monitoring
* Spring Boot Actuator Integration
* Microservices Monitoring

---

## 🛠 Technologies Used

* Java
* Spring Boot
* Spring Boot Admin Server
* Spring Boot Actuator
* Maven
* Eclipse IDE
* Git
* GitHub

---

## 📂 Project Structure

```text
src
 └── main
      ├── java
      │     └── com.aadiandjava
      │            └── AdminServerApplication.java
      │
      └── resources
             └── application.properties
```

---

## 🔄 Admin Server Architecture

```text
                   +----------------------+
                   |   Admin Server       |
                   |     (Dashboard)      |
                   +----------+-----------+
                              ▲
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
        ▼                     ▼                     ▼
 Customer Service      Order Service       Product Service
        │                     │                     │
        └────────── Registers with Admin Server ───┘
```

---

## 📚 Concepts Covered

* Spring Boot Admin
* Spring Boot Actuator
* Microservices Monitoring
* Health Check
* Metrics
* Environment
* Logging
* Centralized Dashboard

---

## 📦 Dependencies

* Spring Boot Starter Web
* Spring Boot Admin Server
* Spring Boot Actuator

---

## ▶️ How to Run

1. Clone the repository.
2. Open the project in Eclipse or IntelliJ IDEA.
3. Update Maven dependencies.
4. Run the Admin Server application.
5. Start the client microservices with Spring Boot Admin Client enabled.
6. Open the Admin Dashboard:

```text
http://localhost:9091
```

*(Replace the port if your application uses a different one.)*

---

## 📸 Output

* Admin Server starts successfully.
* Connected microservices are displayed on the dashboard.
* Health, Metrics, Environment, Beans, and Log information can be viewed from the dashboard.

---

## 👩‍💻 Author

**Monali Babasaheb Palve**
