# 🚀 Codveda Backend SQL – User Management API

## 📌 Project Overview
This project is a backend REST API developed using **Node.js**, **Express.js**, and **Sequelize ORM**, connected to a **remote MySQL database**.

It implements **full CRUD operations** (Create, Read, Update, Delete) for user management and is publicly accessible via **GitHub Codespaces**.

This project was completed as part of the **Codveda Technology Full Stack Development Program (Level 1 & Level 2)**.

---

## 🛠️ Technologies Used
- Node.js
- Express.js
- Sequelize ORM
- MySQL
- GitHub Codespaces
- dotenv

---

## ⚙️ Environment Configuration
Create a `.env` file in the root directory with the following variables:

```env
DB_HOST=your_database_host
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_NAME=your_database_name
DB_PORT=3306
PORT=4000
```
---

## ▶️ How to Run the Project

```bash
npm install
node src/app.js
```
---

## 🔁 API Endpoints

| Method | Endpoint        | Description          |
|------|----------------|----------------------|
| POST | /users          | Create a user        |
| GET  | /users          | Get all users        |
| GET  | /users/:id      | Get user by ID       |
| PUT  | /users/:id      | Update a user        |
| DELETE | /users/:id    | Delete a user        |

---

## ✅ Features
- RESTful API
- Full CRUD operations
- Sequelize ORM
- Remote MySQL database
- GitHub Codespaces deployment

 ---
