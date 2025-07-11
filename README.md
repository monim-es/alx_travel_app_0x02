# alx_travel_app

A real-world Django application serving as the backend for a travel listing platform. This project is part of the ALX Backend Professional Developer program and focuses on scalable project setup, MySQL integration, and automated API documentation.

---

## 🚀 Features

- Modular Django project structure
- MySQL database integration
- REST API with Django REST Framework
- Swagger UI for API documentation (`/swagger/`)
- Environment variable management with `django-environ`
- CORS support with `django-cors-headers`
- Production-ready configuration practices

---

## 🛠️ Tech Stack

- **Backend:** Django, Django REST Framework
- **Database:** MySQL
- **Documentation:** Swagger (drf-yasg)
- **Task Queue (future):** Celery + RabbitMQ
- **Environment Management:** django-environ




====================================================================================================
# 🧳 ALX Travel App — Milestone 5: Background Tasks with Celery & Email Notifications

This project adds **background task management** using **Celery with RabbitMQ** and integrates **email notifications** for booking confirmations.

## 📌 Milestone Objective

- Set up Celery with RabbitMQ as a message broker.
- Trigger a background task when a booking is created.
- Send booking confirmation emails asynchronously.

---

## 🧪 Tech Stack

- Python 3
- Django 4
- Django REST Framework
- Celery
- RabbitMQ
- SMTP (console backend for dev)

---

## 🚀 Setup Instructions

### ✅ 1. Clone the Repo

```bash
git clone https://github.com/monim-es/alx_travel_app_0x03.git
cd alx_travel_app_0x03/alx_travel_app


================================= for the db name : alx_travel_db====================