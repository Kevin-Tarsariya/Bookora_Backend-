# 📚 Bookora – Online Book Store (Backend)

**Bookora Backend** is the server-side application for the Bookora Online Book Store, developed as a college mini project using the **MERN Stack**.

This backend handles authentication, book management, cart operations, and secure API communication with the frontend.

---

## 🚀 Tech Stack

* **Runtime Environment:** Node.js
* **Framework:** Express.js
* **Database:** MongoDB
* **Authentication:** JWT (JSON Web Token)
* **Password Hashing:** bcrypt
* **Environment Management:** dotenv

---

## ✨ Features

* 🔐 User Registration & Login (JWT Authentication)
* 🔑 Secure Password Hashing
* 📚 CRUD Operations for Books
* 🛒 Shopping Cart Management
* 📦 Order Processing APIs
* 🔒 Protected Routes & Middleware
* 🌐 RESTful API Architecture

---

## 📂 Project Structure

```bash id="j82ksl"
Bookora_Book_Store_backend/
│
├── config/
├── controllers/
├── models/
├── routes/
├── middleware/
├── app.js
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

Follow these steps to run the backend locally:

### 1️⃣ Clone the repository

```bash id="c91plx"
git clone https://github.com/your-username/Bookora_Book_Store_backend.git
```

### 2️⃣ Navigate to project folder

```bash id="t6xw2n"
cd Bookora_Book_Store_backend
```

### 3️⃣ Install dependencies

```bash id="q2ns8m"
npm install
```

### 4️⃣ Create a `.env` file in the root directory and add:

```env id="b1ksl9"
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 5️⃣ Start the server

```bash id="l0w8rz"
npm start
```

Server will run on:

```id="u7m2kx"
http://localhost:5000
```

---

## 🔐 API Endpoints Overview

### 👤 Authentication

* `POST /api/auth/register` – Register new user
* `POST /api/auth/login` – Login user

### 📚 Books

* `GET /api/books` – Get all books
* `GET /api/books/:id` – Get single book
* `POST /api/books` – Add new book (Protected)
* `PUT /api/books/:id` – Update book (Protected)
* `DELETE /api/books/:id` – Delete book (Protected)

### 🛒 Cart

* `POST /api/cart` – Add item to cart
* `GET /api/cart` – Get user cart

---

## 🎯 Project Objective

The backend was developed to demonstrate:

* REST API Development
* Database Integration with MongoDB
* Secure Authentication & Authorization
* Real-world E-commerce Backend Architecture

---

## 📌 Future Improvements

* Payment Gateway Integration
* Admin Role Management
* Order History & Invoice Generation
* API Documentation with Swagger
* Deployment on Cloud (Render / AWS / Railway)

---

## 👨‍💻 Author

Developed as part of a Semester Mini Project using the MERN Stack.
