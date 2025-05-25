# alxtravelapp

## 📌 Objective

The **alxtravelapp** project is a real-world Django-based backend application created as part of a learning milestone to simulate industry-grade travel listing platforms. This phase focuses on initializing a robust, modular, and scalable Django project that leverages modern tools and best practices in backend development.

Through this project, learners will:

- Master advanced project initialization and modular settings management.
- Integrate and configure a MySQL database for reliable data persistence.
- Use Swagger (via `drf-yasg`) to provide automated API documentation.
- Set up CORS headers for secure API consumption.
- Prepare for future asynchronous task handling with Celery and RabbitMQ.
- Follow industry best practices for project structure, version control, and collaborative development.

## 📦 Project Scope

This milestone involves the following key deliverables:

### ✅ Project Initialization
- Create a Django project named `alxtravelapp`.
- Add an app named `listings` for core travel listing functionalities.

### 🔧 Dependency Management
Install and configure the following packages:
- `django`: Core web framework.
- `djangorestframework`: For building RESTful APIs.
- `django-cors-headers`: To handle Cross-Origin Resource Sharing.
- `drf-yasg`: For Swagger-based API documentation.
- `celery` and `rabbitmq`: For future asynchronous task handling.
- `django-environ`: For managing environment variables securely.

### ⚙️ Configuration and Tools Integration
- Use `.env` files to manage settings securely.
- Set up MySQL as the default database engine.
- Enable and configure CORS for frontend/backend integration.
- Integrate Swagger for interactive API documentation available at `/swagger/`.

### 🚀 Version Control and Collaboration
- Initialize a Git repository.
- Structure the codebase for team collaboration and maintainability.
- Push the project to a GitHub repository named `alxtravelapp`.

---

## 🛠️ Requirements

Before starting, ensure the following prerequisites are met:

- Familiarity with Django and Django REST Framework.
- Working knowledge of MySQL database management.
- Understanding of Git for version control.
- Basic grasp of managing environment variables with `django-environ`.

---

## 🧰 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/alxtravelapp.git
cd alxtravelapp

# Create a virtual environment
python3 -m venv env
source env/bin/activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit the .env file with your database and secret settings

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver
