# E-Commerce-site-
A simple E-Commerce platform built using Java (console-based backend) and a modern HTML/TailwindCSS frontend. Supports user management, product listing, adding products, placing orders, and viewing orders. Demonstrates core e-commerce logic, clean UI, and seamless interaction between backend structure and frontend functionality.
e-commerce platform
🛍️ E-Commerce Management System
A simple two-part E-Commerce platform built using Java (console-based backend) and HTML + TailwindCSS + JavaScript (frontend dashboard).
This project demonstrates essential e-commerce functionalities such as user management, product handling, orders, and CRUD operations in both console and UI form.
📌 Project Overview
This repository contains two implementations:
1️⃣ Java Console-Based E-Commerce Application
A backend simulation built using core OOP principles.
Includes:
User Management (Admin, Seller, Buyer)
Product listing, adding, updating quantity
Order placement with stock validation
Search and filtering
Sample seeded data
Classes: Platform, User, Product, Order
2️⃣ HTML + TailwindCSS Frontend Dashboard
An interactive, responsive UI representing the same system visually.
Includes:
User list display
Product catalog
Add product UI
Order placement form
Order history
Fully dynamic DOM rendering
Client-side logic using pure JavaScript
📂 Directory Structure
/ECommerce-System
│
├── /java-backend
│   ├── ECommerceApp.java
│   ├── User.java
│   ├── Product.java
│   ├── Order.java
│   └── Platform.java
│
└── /frontend-dashboard
└── index.html
🚀 Features
Common Features
User roles: Admin, Seller, Buyer
Display & manage product inventory
Place orders
Auto-generated IDs (U1, P1, O1)
Sample seeded data in both versions
💻 Java Console App Features
Built entirely using OOP concepts
Console-driven menu
Uses LinkedHashMap for predictable ordering
Validates product stock before order creation
Simple modular structure for learning backend logic
Console Menu
1.	List Users
2.	Show Products
3.	Add Product
4.	Place Order
5.	Show Orders
6.	Exit
🌐 Frontend Dashboard (HTML + TailwindCSS)
Stylish UI using TailwindCSS CDN
Smooth hover animations
Clean card components
Buttons trigger UI updates dynamically
JavaScript stores:
Users
Products
Orders
Live updates shown using DOM manipulation
🧪 Sample Data Included
Users
Admin
Seller: Alice
Seller: Bob
Buyer: Charlie
Products
Wireless Mouse
USB-C Cable
Notebook
Orders
Pre-existing order for Notebook
🛠️ Technologies Used
Backend (Java)
Java 8+
OOP
Collections Framework
Frontend (UI)
HTML5
TailwindCSS
Vanilla JavaScript
▶ How to Run
Java Version
javac ECommerceApp.java
java ECommerceApp
Frontend Version
Open this file in your browser:
frontend-dashboard/index.html
🤝 Contributing
Feel free to suggest features or improvements such as:
Login & authentication
Product search bar
Cart system
REST API backend
Database connectivity
