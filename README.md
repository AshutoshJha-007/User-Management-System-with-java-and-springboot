/* -------------------------
   README.md
------------------------- */
# User Management System

## Overview
A simple **REST API** for managing users, built with **Spring Boot, Hibernate, and MySQL**.

## Features
- CRUD operations for user management.
- Secure authentication (JWT placeholder included).
- Dockerized for easy deployment.
- CI/CD ready with Jenkins/GitHub Actions.

## Setup
### 1. Clone Repository
```sh
git clone https://github.com/yourusername/User-Management-System.git
cd User-Management-System
```

### 2. Configure Database
Update `application.properties` with your MySQL credentials.

### 3. Build and Run
```sh
mvn clean install
java -jar target/user-management.jar
```

### 4. Run with Docker
```sh
docker build -t user-management .
docker run -p 8080:8080 user-management
```

### 5. API Endpoints
| Method | Endpoint       | Description |
|--------|--------------|-------------|
| GET    | /api/users   | Get all users |
| GET    | /api/users/{id} | Get user by ID |
| POST   | /api/users   | Create new user |
| DELETE | /api/users/{id} | Delete user |

## License
This project is open-source under the **MIT License**.

---
