# Week 3 – Express Middleware & MongoDB Integration    

## Topics Covered.    


### 5-Mar-2026     

1. Middlewares in Express
2. Built-in & Custom Middlewares
3. App Level & Route Level Middleware
4. Handling Multiple APIs
5. Introduction to MongoDB
6. MongoDB CRUD Operations

---

### 6-Mar-2026

1. Connecting REST API with MongoDB Database
2. MongoDB Native Driver vs Mongoose ODM Driver
3. Creating Schema & Model
4. Schema Validations and Indexing
5. USER REST API Implementation
6. Hashing Passwords
7. Error Handling Middleware
8. Handling Unavailable Resources
9. Running Validators During Update Operations

---

# Assignments

## 1. MongoDB Query Practice

Practice MongoDB queries including:

* Insert documents
* Read documents
* Update documents
* Delete documents
* Filtering and querying collections

---

## 2. Product REST API Assignment

Create a **Product REST API** with the following features.

### Product Document Structure

```json
{
  "productId": "required",
  "productName": "required",
  "price": "required (min: 10000, max: 50000)",
  "brand": "required"
}
```

---

### API Operations

1. Create Product
2. Read All Products
3. Read Product by **productId**
4. Update Product by **productId**
5. Delete Product by **productId**

---

# Additional Concepts Implemented

* Express Middleware
* Error Handling Middleware
* Password Hashing
* MongoDB with Mongoose
* Schema Validations
* Indexing in MongoDB

---

# Example Project Structure

```
week3
 ├── config
 │   └── database.js
 ├── models
 │   └── productModel.js
 ├── routes
 │   └── productRoutes.js
 ├── controllers
 │   └── productController.js
 ├── middleware
 │   └── errorMiddleware.js
 ├── server.js
 └── README.md
```

---

# Technologies Used

* JavaScript (ES6)
* Node.js
* Express.js
* MongoDB
* Mongoose

---

# Author

JavaScript Practice – Week 3
