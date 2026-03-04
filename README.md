# 🛒 E-Commerce Backend API

Professional backend service for a full-stack E-Commerce web application.

## 🚀 Live Application

Frontend (Live): https://ecommerce-frontend-rose-three.vercel.app/

---

## 📌 Project Overview

This backend provides RESTful APIs for an E-Commerce platform including:

* User authentication
* Product management
* Cart operations
* Order processing
* MySQL database integration

The server is built using Node.js and Express and connects to a MySQL database.

---

## 🛠 Tech Stack

* Node.js
* Express.js
* MySQL
* CORS
* dotenv (Environment Variables)

---

## 📂 Project Structure

```
backend/
│── server.js
│── db.js
│── package.json
│── routes/
│     ├── auth.js
│     ├── orders.js
│     └── products.js
```

---

## ⚙️ Installation (Local Setup)

### 1️⃣ Clone Repository

```
git clone <your-backend-repo-url>
cd ecommerce-backend
```

### 2️⃣ Install Dependencies

```
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the root folder:

```
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=ecommerce_db
PORT=5000
```

### 4️⃣ Run Server

```
npm start
```

Server runs on:

```
http://localhost:5000
```

---

## 🌍 Deployment

Backend deployed on Railway.

Environment variables are configured in the Railway dashboard.

Production setup includes:

* Cloud MySQL database
* Environment variable configuration
* Automatic deployment from GitHub

---

## 🔐 API Endpoints

### Authentication

* POST /api/register
* POST /api/login

### Products

* GET /api/products

### Orders

* POST /api/orders
* GET /api/orders/:userId

---

## 📦 Database Tables

* users
* products
* orders
* order_items

---

## 💼 Resume Description

Designed and developed a production-ready E-Commerce backend system with secure REST APIs, MySQL database integration, and cloud deployment. Implemented authentication, order management, and scalable architecture using Node.js and Express.

---

## 📧 Author

MANYAM SIVA SANTHOSH KUMAR REDDY
GMail: sivasanthoshmanyam48@gmail.com
LinkedLn : https://www.linkedin.com/in/manyam-siva-santhosh-kumar-reddy-297a9531b
GitHub: https://github.com/99220040626/

---

## 📜 License

This project is licensed for educational and portfolio purposes.
