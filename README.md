# ☕ Coffee Shop Management System

## 📌 Project Overview

The **Coffee Shop Management System** is a full-stack web application built using **Python (Django)** that allows users to browse menu items, place orders, and manage billing efficiently.
It also provides an admin interface to manage products, orders, and customers.

---

## 🚀 Features

* 🛒 Browse coffee menu with images and prices
* ➕ Add items to cart and place orders
* 💳 Generate bills and order summaries
* 📦 Track order status
* 🔐 Admin panel for managing menu and orders
* 👤 User authentication (Login/Register) *(if implemented)*

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript, Bootstrap
* **Backend:** Python, Django
* **Database:** SQLite / PostgreSQL
* **Tools:** Git, GitHub
* **API Testing:** Postman

---

## 📂 Project Structure

```
coffee-shop/
│── coffee_shop/        # Project settings
│── app/                # Main application
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   └── static/
│
│── db.sqlite3
│── manage.py
│── requirements.txt
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/coffee-shop.git
cd coffee-shop
```

---

### 2️⃣ Create virtual environment

```bash
python -m venv venv
```

Activate it:

```bash
venv\Scripts\activate   # Windows
```

---

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Apply migrations

```bash
python manage.py migrate
```

---

### 5️⃣ Run the server

```bash
python manage.py runserver
```

👉 Open browser: http://127.0.0.1:8000/

---

## 🔗 Key Functionalities

* View menu items
* Add to cart
* Place orders
* Admin can manage products and orders

---

## 📸 Future Enhancements

* Online payment integration (Razorpay/Stripe)
* Order history for users
* REST API using Django REST Framework
* Deployment on AWS / Render

---

## 👨‍💻 Author

**Sachin H M**

* Full Stack Developer
* 📧 [hmsachin300@gmail.com](mailto:hmsachin300@gmail.com)
* 🔗 LinkedIn: https://www.linkedin.com/in/sachin-hm-8767a82b6/

---

## ⭐ Contributing

Contributions are welcome! Feel free to fork and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.
