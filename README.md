# Custom API Server

## 🔧 Description
A Node.js + Express server with MongoDB Atlas integration. Provides 4 custom API endpoints for CRUD operations on `items`. Includes a minimal HTML+JS frontend.

## 🚀 Features
- Create, read, update, and delete items via custom APIs
- Simple web frontend to add and view items
- Connected to MongoDB Atlas (cloud-hosted DB)
- API tested using Postman

## 🛠 Technologies Used
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- HTML, CSS, JavaScript (Frontend)
- Postman (API testing)

## 🔗 API Endpoints

| Method | Endpoint         | Description        |
|--------|------------------|--------------------|
| POST   | `/api/items`     | Add a new item     |
| GET    | `/api/items`     | Get all items      |
| PUT    | `/api/items/:id` | Update an item     |
| DELETE | `/api/items/:id` | Delete an item     |

## ▶️ How to Run the Project

### Backend (API Server)

```bash
git clone https://github.com/arunava03/apiserver.git
cd apiserver
npm install
node server.js
