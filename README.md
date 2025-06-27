# 📦 Custom API Server with MongoDB, Tests, and Frontend

This project is a full-stack application that includes a Node.js + Express API server with MongoDB integration, frontend interaction, and thorough automated tests (unit, integration, and API). It provides full CRUD functionality for managing items.

## 🚀 Features

- ✅ Custom REST API with 4 CRUD endpoints
- 🗃️ MongoDB Atlas for cloud database storage
- 🌐 Minimal HTML Frontend to interact with API
- 🧪 Automated Testing using Jest and Supertest
- 📊 Test Coverage Report (85%+ coverage)

## 🛠 Tech Stack

- **Backend:** Node.js, Express  
- **Database:** MongoDB Atlas, Mongoose  
- **Frontend:** HTML, CSS, JavaScript  
- **Testing:** Jest, Supertest  
- **Environment Management:** dotenv  
- **Manual API Testing:** Postman  

## 🔗 API Endpoints

| Method | Endpoint         | Description             |
|--------|------------------|-------------------------|
| POST   | `/api/items`     | Create a new item       |
| GET    | `/api/items`     | Get all items           |
| PUT    | `/api/items/:id` | Update an existing item |
| DELETE | `/api/items/:id` | Delete an item          |

## ▶️ How to Run the Project

### Backend (API Server)

```bash
git clone https://github.com/arunava03/apiserver.git
cd apiserver
npm install
node server.js
