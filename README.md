# 🛒 ProCart Backend | Scalable E-Commerce REST API

A robust, production-ready backend service designed to power modern E-Commerce applications. This RESTful API handles secure user authentication, relational data management, and real-time order processing with a cloud-hosted MySQL database.

---

## 🔗 Live Links

**Backend API (Production):**
[https://ecommerce-project-jl8v.onrender.com/](https://ecommerce-project-jl8v.onrender.com/)

**Frontend Client:**
[https://ecommerce-frontend-rose-three.vercel.app/](https://ecommerce-frontend-rose-three.vercel.app/)

---

## 🛠 Tech Stack & Architecture

**Runtime & Framework**

* Node.js
* Express.js

**Database**

* MySQL (Hosted via Aiven Cloud)

**Security**

* SSL/TLS encrypted database connections
* Secure credential management using environment variables
* Protected API endpoints

**DevOps & Deployment**

* CI/CD pipeline integrated with GitHub
* Production deployment via Render
* Environment-based configuration for seamless development-to-production transition

**API Design**

* RESTful architecture
* JSON-based request and response handling
* Modular route structure

---

## 📂 Project Structure

```
backend/
├── routes/           # API route definitions (Auth, Orders, Products)
├── db.js             # Singleton database connection logic (SSL enabled)
├── server.js         # Express server entry point & middleware configuration
└── .env              # Environment variables (not committed)
```

---

## 🔐 Core Features & Endpoints

### 👤 Authentication

* **POST /api/register**
  New user registration with database validation and secure storage.

* **POST /api/login**
  Secure credential verification and authentication handling.

---

### 📦 Product Management

* **GET /api/products**
  Dynamic retrieval of product catalog data from MySQL.

---

### 🧾 Order Fulfillment

* **POST /api/orders**
  Transactional processing of customer purchases with relational mapping.

* **GET /api/orders/:userId**
  Retrieves user-specific orders using SQL JOIN operations to combine relational datasets.

---

## 🗄 Database Schema (Relational Design)

The system follows a structured relational schema to maintain data integrity and scalability:

* **Users**
  Stores profile information and authentication credentials.

* **Products**
  Manages product inventory and pricing data.

* **Orders**
  Transactional order headers linked via `user_id` (Foreign Key).

Relational mapping ensures accurate linkage between users and their respective purchases.

---

## ⚙️ Environment Configuration

Production credentials are managed securely via environment variables:

```
DB_HOST=
DB_USER=
DB_PASSWORD=
DB_NAME=
PORT=
```

Sensitive data is excluded from version control to maintain security best practices.

---

## 🚀 Deployment Highlights

* Configured SSL-enabled MySQL connection for secure cloud communication
* Resolved production-level database handshake and certificate validation issues
* Implemented environment-specific configuration handling
* Established automated CI/CD workflow for continuous deployment

---

## 💼 Professional Summary (For Resume)

**Full-Stack E-Commerce Backend Developer**

Engineered a scalable REST API using Node.js and Express, integrated with a cloud-hosted MySQL database. Designed relational data models and implemented SQL JOIN operations for efficient order-user mapping. Resolved complex deployment challenges including SSL database connectivity and environment configuration across development and production environments. Successfully deployed the application using CI/CD practices on Render.

---

## 👨‍💻 Author

Manyam Siva Santhosh Kumar Reddy

GitHub: [https://github.com/99220040626](https://github.com/99220040626)

LinkedIn: [https://linkedin.com/in/manyam-siva-santhosh-kumar-reddy](https://www.linkedin.com/in/manyam-siva-santhosh-kumar-reddy-297a9531b)

Email: [sivasanthoshmanyam48@gmail.com](mailto:sivasanthoshmanyam48@gmail.com)

---

## 📜 License

This project is developed for educational, portfolio, and demonstration purposes.
