# Introduction to Django

# Creating a first Django Project

- mkdir <folderName>
- pipenv install django

# Activate the virtual environment

- pipenv shell
- django-admin (view core commands)
- django-admin startproject storefront .
- python manage.py runserver

---###---###---###---###

# Source: Tech with Tim

- mkdir <folderName>
- python -m venv env
- env/Scripts/activate
- django-admin startproject backend
- cd backend
- COPY AND PASTE REQUIREMENTS to requirements.txt
- pip install -r requirements.txt
- python manage.py startapp api

# Creating a new user

- See serializers.py
- See views.py
- See urls.py

# Migration

- python manage.py makemigrations
- python manage.py migrate
