# 📝 Note-Taker

A full-stack note-taking application built with the **MERN** stack.

---

## 🧱 Tech Stack

**MERN** = MongoDB + Express + React + Node.js

### 🔹 Frontend

- **React.js** – JavaScript library for building user interfaces

### 🔹 Backend

- **Node.js** – JavaScript runtime for running JS on the server
- **Express.js** – Web framework that simplifies building APIs and handling routing, middleware, etc.

  **Why Express?**

  - Saves development time
  - Keeps code cleaner and more organized
  - Handles common tasks like routing and error handling

### 🔹 Database

- **MongoDB** – NoSQL database for flexible, JSON-like document storage

---

## 🔌 API Overview

### What is an API?

- An **Application Programming Interface** allows two different applications to communicate with each other.

### REST API

- Uses standard HTTP methods:

| Method | Description          |
| ------ | -------------------- |
| GET    | Retrieve data        |
| POST   | Create new data      |
| PUT    | Update existing data |
| DELETE | Remove data          |

---

## ✅ HTTP Status Codes

### 1xx – Informational

- Request received, continuing process

### 2xx – Success

- **200 OK** – Request succeeded
- **201 Created** – Resource successfully created (e.g., after a POST)

### 3xx – Redirection

- Server is redirecting the client
- **301 Moved Permanently** – e.g., redirect from `http://` to `https://`

### 4xx – Client Errors

- The issue is on the client side
- **400 Bad Request** – Malformed or invalid request
- **401 Unauthorized** – Missing or invalid credentials
- **403 Forbidden** – Access denied
- **404 Not Found** – Resource doesn't exist
- **429 Too Many Requests** – Rate limit exceeded

### 5xx – Server Errors

- The issue is on the server side
- **500 Internal Server Error** – Server encountered an unexpected condition
- **503 Service Unavailable** – Server is temporarily overloaded or down

---

## 🗃️ SQL vs NoSQL

### SQL (Structured Data)

- Data stored in tables with rows and columns
- Uses SQL language (e.g., SELECT, INSERT)
- Best for complex queries and relational data (e.g., orders and customers)

### NoSQL (Flexible Data)

- Stores data as JSON or key-value pairs
- Uses custom query languages or APIs
- Best for big data and real-time applications

---

## 🔐 CORS (Cross-Origin Resource Sharing)

- A browser security feature
- Prevents websites from accessing resources from another domain unless explicitly allowed
- Common issue when frontend and backend are hosted separately

---

## 🚀 Deployment Model

- Both frontend and backend are hosted on the same domain

---

## 🛠️ Notes

- Used **daisyUI** for theming
- Used **lucide** for icons
- Used **toast** for notifications
