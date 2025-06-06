# 📦 Product RESTful API – Express.js Assignment (Week 2)

This project is a RESTful API built with **Express.js** for managing a product catalog. It includes full CRUD operations, middleware (logging, authentication, error handling), and advanced features like filtering, search, and pagination.

---

## 🚀 Getting Started

### 📦 Install Dependencies

Make sure you have **Node.js (v18 or higher)** installed. Then open your terminal in the project folder and run:

```bash
npm install


🧰 Features
✅ CRUD Operations
Create, Read, Update, and Delete products.

🔍 Advanced Features
Filtering by category and in-stock status:
GET /api/products?category=electronics&inStock=true

Search by product name:
GET /api/products?search=laptop

Pagination with page & limit:
GET /api/products?page=1&limit=2

🛡️ Middleware
Logger – Logs each incoming request.

Authentication – Protects sensitive routes using a bearer token.

Validation – Ensures all required fields are present in requests.

Error Handling – Catches and formats errors as clean responses.

