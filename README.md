

# 🛒 E-Commerce Online Shopping

A Django-based E-Commerce Online Shopping Web Application that allows customers to browse products, search for products, manage their cart, place orders, track orders, and manage their accounts.

## 📌 Project Overview

This project is developed using **Python and Django** to provide a simple and user-friendly online shopping platform.

Customers can register and log in, browse products, search products, add products to the cart, update quantities, proceed to checkout, track orders, submit reviews, and contact the store.

## ✨ Features

* 👤 Customer Registration & Login
* 🔐 User Authentication
* 🛍️ Product Listing
* 🔎 Product Search
* 📦 Product Details
* 🛒 Add to Cart
* ➕ Increase / Decrease Cart Quantity
* 💰 Cart Total Calculation
* 🧾 Checkout
* 📍 Shipping Address Details
* 💳 Payment Method Selection
* 🚚 Order Tracking
* ⭐ Product Reviews
* 🔑 Change Password
* 📞 Contact Form
* 👤 Customer Profile Management
* 🛠️ Django Admin Panel
* 🗄️ SQLite Database

## 🛠️ Technologies Used

### Backend

* Python
* Django

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Database

* SQLite

### Tools

* Visual Studio Code
* Git
* GitHub

## 📂 Project Structure

```text
E-Commerce-Online-Shopping/
│
├── OnlineShopping/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── shop/
│   ├── migrations/
│   ├── media/
│   ├── static/
│   ├── templates/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── admin.py
│   └── tests.py
│
├── manage.py
├── README.md
└── .gitignore
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/pragatisk1806-blip/E-Commerce-Online-Shopping.git
```

### 2. Open the Project

```bash
cd E-Commerce-Online-Shopping
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### macOS / Linux

```bash
source venv/bin/activate
```

### 5. Install Required Packages

```bash
pip install django pillow
```

### 6. Apply Migrations

```bash
python manage.py migrate
```

### 7. Start the Development Server

```bash
python manage.py runserver
```

### 8. Open in Browser

```text
http://127.0.0.1:8000/
```

## 🛍️ Main Modules

### Customer Module

* Registration
* Login / Logout
* Change Password
* Customer information

### Product Module

* Product listing
* Product details
* Product search
* Product reviews

### Shopping Cart

* Add products
* Update quantity
* Remove products
* Calculate total amount

### Checkout & Orders

* Shipping information
* Payment method selection
* Order creation
* Order tracking

### Contact Module

* Contact form
* Logged-in customer contact functionality

## 🗄️ Database Models

The application includes models for:

* Customer
* Product
* Feature
* Review
* Order
* OrderItem
* UpdateOrder
* CheckoutDetail
* Contact

## 🚀 Future Enhancements

The project can be further enhanced with:

* Online payment gateway integration
* Product categories
* Wishlist functionality
* Product ratings
* Vendor management
* Email notifications
* REST API
* Django REST Framework
* Deployment on cloud platforms
* Advanced admin dashboard

## 👩‍💻 Author

**Pragati Kharat**

GitHub:
https://github.com/pragatisk1806-blip

## 📄 License

This project is developed for educational and portfolio purposes.

























Project Repo
