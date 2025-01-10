Task Management API
A Django-based REST API for managing tasks, with authentication implemented using Django's built-in authentication system or token-based authentication (JWT).

Features
User registration and login.
Task creation, update, deletion, and retrieval.
Authentication using Django Rest Framework (DRF) and djangorestframework-simplejwt.
Secure access to protected endpoints using tokens.
Getting Started
Prerequisites
Python 3.9+ installed on your machine.
pip for installing Python packages.
A virtual environment for dependency management.
Installation Steps
Clone the Repository:

bash
Copy code
git clone <repository_link>
cd Task-Management-API
Set Up Virtual Environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Apply Migrations:

bash
Copy code
python manage.py migrate
Create a Superuser:

bash
Copy code
python manage.py createsuperuser
Run the Development Server:

bash
Copy code
python manage.py runserver
