# Locker It – Smart Second-Hand Commerce Platform

**Locker It** is a full-stack web platform that blends modern e-commerce features with second-hand trading. It enables users to list products for sale, manage orders, and complete the delivery through smart logistic lockers 
— ensuring a safe and contactless experience.

---

## Key Features

-  Second-hand product marketplace with real-time status updates
-  Locker-based logistics – no direct contact between buyer and seller
-  Secure image upload via AWS S3
-  JWT Authentication (Access & Refresh tokens stored in HTTP-only cookies)
-  User & Admin role separation
-  Purchase queue tracking, time estimates, and real-time alerts
-  Swagger API documentation with multiple examples and error schemas

---

## Tech Stack

### Backend (Node.js & Express)
- Express.js with MVC architecture
- MongoDB using Mongoose
- JWT authentication with cookie-based security
- Swagger (OpenAPI 3.0) for full API documentation
- Docker support with Docker Compose

### Frontend (React)
- React with functional components and hooks
- MUI (Material UI) for building the UI
- Redux Toolkit (RTK) for state management
- Integrated with secure backend using cookie-based auth

---

## Docker Support

- **Dockerized environment** for both client and server
- **Docker Compose** configuration for local development
- Simplified onboarding and consistent environment setup across developers

---

## Project Repositories

### Frontend
> [github.com/colman-dev-project/Front](https://github.com/Locker-It/Front)

### Backend
> [github.com/colman-dev-project/Back](https://github.com/Locker-It/Back)

---

## Project Goals

- Deliver a safe, modern second-hand trading platform
- Ensure a seamless user experience without direct communication between users
- Build a production-grade architecture ready for scaling and deployment
