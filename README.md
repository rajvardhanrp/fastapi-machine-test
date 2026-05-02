# 🚀 FastAPI Machine Test

## 📌 Project Overview
This project is a FastAPI backend application implementing CRUD operations for Categories and Products with PostgreSQL database.

---

## 🛠 Tech Stack
- FastAPI
- PostgreSQL
- SQLAlchemy
- Pydantic
- Uvicorn

---

## ✨ Features
- Category CRUD APIs
- Product CRUD APIs
- One-to-Many Relationship (Category → Products)
- Pagination support

---

## 📂 Project Structure
```
app/
│── main.py
│── database.py
│── models.py
│── schemas.py
│── crud.py
└── routes/
    ├── category.py
    └── product.py
```

---

## ⚙️ Setup Instructions

### Clone Repo
```
git clone https://github.com/dalvianiket10/fastapi-machine-test.git
cd fastapi-machine-test
```

### Install Dependencies
```
pip install -r requirements.txt
```

### Run Server
```
uvicorn app.main:app --reload
```

---

## 📡 API Endpoints

### Categories
- POST /api/categories/
- GET /api/categories/
- GET /api/categories/{id}
- PUT /api/categories/{id}
- DELETE /api/categories/{id}

### Products
- POST /api/products/
- GET /api/products/
- GET /api/products/{id}
- PUT /api/products/{id}
- DELETE /api/products/{id}

---

## 👨‍💻 Author
Rajvardhan Patil
