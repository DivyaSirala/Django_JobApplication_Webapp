# Django Job Application Webapp

## Overview
This Django web application project is designed for managing job applications. Users can submit their applications through the provided forms, and administrators can review and manage these applications through the admin interface.

## Directory Structure
```
Project
|-- job_application
|   |-- migrations
|   |-- templates
|   |-- __init__.py
|   |-- admin.py
|   |-- apps.py
|   |-- forms.py
|   |-- models.py
|   |-- tests.py
|   |-- urls.py
|   |-- views.py
|-- JobPortal
|   |-- __pycache__
|   |-- __init__.py
|   |-- asgi.py
|   |-- settings.py
|   |-- urls.py
|   |-- wsgi.py
|-- venv
|-- db.sqlite3
|-- manage.py
```

## Instructions

### 1. How to Use the Given Code
- Clone this repository to your local machine using Git:
  ```
  git clone <repository_url>
  ```
- Navigate to the project directory:
  ```
  cd Project
  ```
- Install the required dependencies using pip:
  ```
  pip install -r requirements.txt
  ```
- Create a virtual environment (optional but recommended):
  ```
  python3 -m venv venv
  source venv/bin/activate
  ```
- Start the Django development server:
  ```
  python manage.py runserver
  ```

### 2. How to Run the Python Code on Server Using "python manage.py"
- Navigate to the project directory if you haven't already:
  ```
  cd Project
  ```
- Start the Django development server:
  ```
  python manage.py runserver
  ```

### 3. How to Open the Admin Server for the Django File
- Once the development server is running, open a web browser and go to the following URL:
  ```
  http://127.0.0.1:8000/admin/
  ```
- Log in using your admin credentials.
- You should now have access to the Django admin interface where you can manage job applications and other aspects of the application.


