# Springboot-Basics

This is a comprehensive repository dedicated to mastering the Spring Boot ecosystem, from core fundamentals to advanced architectural patterns. This project serves as a structured learning journey into building scalable, secure, and production-ready backend services.

## Tech Stack

- **Framework:** Spring Boot 3.5+
- **Security:** Spring Security, JSON Web Tokens (JWT)
- **Environment Management:** Dotenv (.env)
- **Build Tool:** Maven

## Project Structure

This is a monorepo containing multiple independent Spring Boot modules:

* **wingsdemo**: A secure REST API featuring custom JWT authentication, externalized configuration, and a stateless session architecture.
* *(More modules coming soon...)*

## Features

- **Production-Ready Security:** Implementation of JWT-based authentication with stateless session management.
- **Externalized Configuration:** Secure handling of sensitive data (like secret keys) using `.env` files and environment variables.
- **Clean Architecture:** Well-organized project structure following industry-standard package naming and separation of concerns.
- **Modular Design:** Scalable monorepo setup allowing for easy addition of new learning modules.

## Setup & Run Instructions

### 1. Clone the repository
```bash
git clone [https://github.com/AyanMajumdar100/springboot-basics.git](https://github.com/AyanMajumdar100/springboot-basics.git)
cd springboot-basics

```

### 2. Configure Environment Variables

Create a `.env` file in the project root to store your sensitive keys. This file is ignored by Git for security.

```text
# Example .env content
JWT_SECRET=8367566B59703373367639792F423F4528482B4D6251655468576D5A71347439

```

### 3. Run the Application

Navigate to the specific project folder and run using Maven:

```bash
cd wingsdemo
./mvnw spring-boot:run

```

---

Built for practice, learning, and mastering Backend Development.
