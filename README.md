# 🍽️ CraveKart

CraveKart is a full-stack food ordering web application built with Django and Django REST Framework. Users can browse restaurants, search by cuisine or location, add food items to their cart, place orders, and view order history. The project also provides REST APIs with Swagger documentation and is deployed on Render using a Neon PostgreSQL database.

## 🌐 Live Demo

**Website:** https://cravekart-1.onrender.com

**Swagger API:** https://cravekart-1.onrender.com/swagger/

**Admin Panel:** https://cravekart-1.onrender.com/admin/

---

# ✨ Features

- User Registration & Login
- Restaurant Listing
- Search Restaurants
- Restaurant Details
- Add to Cart
- Increase/Decrease Quantity
- Payment Page
- Order Placement
- Order History
- Django Admin Dashboard
- REST APIs
- Swagger Documentation
- Responsive UI
- PostgreSQL Database
- Live Deployment on Render

---

# 🛠 Tech Stack

## Backend
- Python
- Django
- Django REST Framework

## Frontend
- HTML5
- CSS3
- Bootstrap 5

## Database
- PostgreSQL (Neon)

## API Documentation
- drf-yasg (Swagger)

## Deployment
- Render
- Gunicorn
- WhiteNoise

## Version Control
- Git
- GitHub

---

# 📁 Project Structure

```
CraveKart/
│
├── core/
├── users/
├── templates/
├── static/
├── zomato_clone/
├── manage.py
├── requirements.txt
├── build.sh
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/rohan00112233/CraveKart.git
```

Move into the project

```bash
cd CraveKart
```

Create virtual environment

```bash
python -m venv venv
```

Activate virtual environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Apply migrations

```bash
python manage.py migrate
```

Create superuser

```bash
python manage.py createsuperuser
```

Run the server

```bash
python manage.py runserver
```

---

# 🔑 Environment Variables

Create a `.env` file and add the following:

```env
SECRET_KEY=your_secret_key

DEBUG=False

DATABASE_URL=your_neon_database_url

RAZORPAY_KEY_ID=your_key

RAZORPAY_KEY_SECRET=your_secret
```

---

# 📡 REST API Endpoints

| Method | Endpoint |
|---------|----------|
| GET | /api/restaurants/ |
| GET | /api/restaurants/<id>/ |
| POST | /api/add-restaurant/ |
| PUT | /api/update-restaurant/<id>/ |
| DELETE | /api/delete-restaurant/<id>/ |

---

# 📖 API Documentation

Swagger UI

```
/swagger/
```

ReDoc

```
/redoc/
```

---

# 🗄 Database

The application uses **Neon PostgreSQL** for production.

Local development can use PostgreSQL or MySQL by updating the database configuration.

---

# 🚀 Deployment

The application is deployed using:

- Render
- Gunicorn
- WhiteNoise
- Neon PostgreSQL

---



# 🎯 Future Enhancements

- Razorpay Payment Gateway Integration
- Restaurant Reviews & Ratings
- Wishlist
- Coupons & Discounts
- Email Notifications
- User Profile Management
- Order Tracking
- Docker Support
- CI/CD Pipeline
- AWS Deployment

---

# 👨‍💻 Author

**Rohan Shinde**

GitHub: https://github.com/rohan00112233



---

# 📄 License

This project is licensed under the MIT License.