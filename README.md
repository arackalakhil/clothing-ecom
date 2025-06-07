# 🛍️ Clothing E-Commerce API (Django REST Framework)

This is a Django-based e-commerce backend API built using **Django REST Framework**.  
It is structured to support clothing and fashion-based products, with modular apps for `user` and `product` management.

---

## 🚀 Features

- Modular Django project with separate apps:
  - `user`: handles user-related logic (login, registration, etc.)
  - `product`: handles product creation, listing, and management
- RESTful APIs using Django REST Framework
- Easily extendable for categories, orders, carts, payments, etc.
- Secure authentication-ready setup (JWT or token-based can be added)

---

## 🗂️ Project Structure

clothing-ecom/
│
├── ecom/ # Main Django project
├── user/ # Custom user app (auth, profile)
├── product/ # Product management app
├── env/ # Virtual environment (excluded in .gitignore)
├── manage.py # Django project manager
└── requirements.txt (recommended)

---

## ⚙️ Setup Instructions

```bash
# Clone the repository
git clone https://github.com/arackalakhil/clothing-ecom.git
cd clothing-ecom

# Create virtual environment
python -m venv env
source env/bin/activate      # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start development server
python manage.py runserver
