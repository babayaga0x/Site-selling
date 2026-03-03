# 🛒 Site Selling — E-Commerce Web Application

A full-stack internet shop built with vanilla HTML, CSS, and JavaScript on the frontend, backed by a server and database for managing products, orders, and users.

---

## 📌 Description

**Site Selling** is a web-based e-commerce platform that allows users to browse products, add them to a cart, and place orders. The project includes a fully functional backend with database integration for persistent data storage.

---

## 🧠 Features

- 🛍️ Product catalog with listings
- 🛒 Shopping cart functionality
- 👤 User registration and authentication
- 📦 Order management
- 🗄️ Backend API with database support
- 📱 Responsive UI with HTML / CSS / JS

---

## 🛠 Technologies Used

| Layer      | Technology          |
|------------|---------------------|
| Frontend   | HTML, CSS, JavaScript |
| Backend    | Server-side API     |
| Database   | Relational DB (SQL) |
| Deployment | Local / Docker      |

---

## 🚀 Quick Start

### Requirements

- Git
- A running backend server (see backend setup)
- A modern web browser

### Clone the Repository
```bash
git clone https://github.com/babayaga0x/Site-selling.git
cd Site-selling
```

### Run the Project

Open `index.html` in your browser directly, or serve it with a local server:
```bash
# Using Python
python3 -m http.server 8080

# Using Node.js (npx)
npx serve .
```

Then open `http://localhost:8080` in your browser.

---

## ⚙️ Backend & Database Configuration

Make sure your backend server is running and the database is configured. Update the API base URL in the frontend config file (e.g., `config.js` or `api.js`):
```javascript
const API_BASE_URL = "http://localhost:3000"; // change to your backend URL
```

Set up your database connection on the backend side with the appropriate credentials:
```
DB_HOST=localhost
DB_PORT=5432
DB_NAME=site_selling
DB_USER=your_username
DB_PASSWORD=your_password
```

---

## 📁 Project Structure
```
Site-selling/
├── index.html          # Main entry point
├── css/
│   └── style.css       # Global styles
├── js/
│   └── main.js         # Frontend logic
├── pages/              # Additional pages (cart, product, etc.)
├── assets/             # Images and static files
└── README.md
```

---

## 🧪 Testing

Automated tests are not yet included. Manual testing is recommended for:

- Product listing and filtering
- Cart add / remove / update
- Order placement flow
- User login and registration

---

## 📈 Goals

This project can be used as:

- A learning project for full-stack web development
- A template for building e-commerce applications
- A foundation for adding payment systems (Stripe, PayPal, etc.)

---

## 📄 License

This project is open source. Feel free to fork, modify, and use it for your own purposes.
