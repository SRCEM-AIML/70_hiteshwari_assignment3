Flask & Django with Docker Compose
Overview
This project demonstrates how to create and containerize web applications using Flask and Django, managed with Docker Compose.

Flask Application
A simple Flask web application with:
A homepage displaying "Hello, World!"
A form to accept a user's name and age, returning a greeting message
Basic error handling for invalid inputs
Django Application
A basic Django project with:
A homepage displaying a list of items stored in a database
An admin panel to add and modify items
A form on the homepage to add a new item
Setup & Run
Prerequisites
Install Docker
Install Docker Compose
Running with Docker Compose
Clone the repository: git clone https://github.com/SRCEM-AIML/70_hiteshwari_assignment3
Build and start the containers: docker-compose up --build
Access the applications:
Flask app: http://localhost:5000
Django app: http://localhost:8000
Running Containers Individually
Flask
Build the Flask image: docker build -t flask_app ./flask_app
Run the Flask container: docker run -p 5000:5000 flask_app
Django
Build the Django image: docker build -t django_app ./django_app
Run the Django container: docker run -p 8000:8000 django_app
Docker Hub & GitHub
GitHub Repository: GitHub Repo
Docker Hub:
Django App
Flask App
