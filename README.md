# Django Band Website

## Table of Contents
- [Project Description](#project-description)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Project Author](#project-author)

## Project Description
This is a Django-based website project for creating a website for a fictional band.

## Project Structure
- `capstone/`: Django project settings and configurations.
- `band/`: Django app for the band website.
- `templates/`: HTML templates for your website pages.
- `static/`: Static files (CSS, JavaScript, images, etc.).

## Installation
To run this project on your local system, follow these steps:

1. Clone the repository from GitHub:
   - gh repo clone nokuthabam/django-band-website
     
2. Install project dependencies:
   - pip install -r requirements.txt
     
2. Installing Django and creating virtual environment:
   - mkvirtualenv my_django
   -  workon my_django
   -   pip install django
  
2. Navigate to the project directory:
   - cd django-band-website/capstone

3. Apply database migrations:
   - python manage.py migrate

4. Create a superuser to manage the Django admin panel:
   - python manage.py createsuperuser

5. Start the development server:
   - python manage.py runserver

6. Access the website at http://127.0.0.1:8000/

## Usage
   - http://127.0.0.1:8000/ will take you to the landing page
   - Clicking explore will take you to the login page where you can choose to sign up  or log in if you have credentials
   - Once logged in, you will be able to access the website and navigate through the different pages
   -  
## Project Author
Nokuthaba Moyo



