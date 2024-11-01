# Recipes App

### INF601 - Advanced Programming in Python
### Sokly Hour
### Mini Project 4

## Overview
The Recipes App is a small web application built using Django that allows users to browse, add, and manage their favorite recipes. Some key features of the application include:

**User Authentication**: Users can create accounts and securely log in, ensuring that their personal recipe collections are safe and accessible only to them.

**Recipe Management**: Users can add, view, edit, and delete their favorite recipes, allowing for easy management of their culinary creations.

**Responsive Design**: The application is designed with Bootstrap, ensuring a seamless and user-friendly experience across all devices. Its visually appealing interface enhances usability, while a **Bootstrap modal featured in the About page(feature section)** encourages user engagement by providing additional information in an interactive format.

**SQLite Database**: The application uses a SQLite database to store user information and recipe records, ensuring efficient data management. The database includes tables for user data and recipes, linked via foreign keys.

**Multi-page Application**: The app consists of at least five pages, including the home page, login page, registration page, recipe creation page, and an about page.

## Getting Started

The running environment and all dependencies can be obtained through the command console in the Python IDE of your choosing.

### Step 1: Pip install requirements.txt
Before getting started, you will need to install this application's dependencies.

In a terminal window, please type the following:
```bash
pip install -r requirements.txt
```
### Step 2: Create SQL entries needed for the database

The SQLite database is not yet in the project, you will need to generate a migration to tell Django which model variables need to be added to the database.

In a terminal window, please type the following:
```bash
python manage.py makemigrations
```

### Step 3: Apply the migrations to the SQL database
Now, you need to apply those migrations to the project.

In a terminal window, please type the following:
```bash
python manage.py migrate 
```

### Step 4: Create a super user
Before you start using the program, you will need to generate a superuser account so that you can add users through the admin interface.

In a terminal window, please type the following:
```bash
python manage.py createsuperuser 
```

### Step 5: Start the server
Now, you will need to start the development server that will be hosting this webapp.

In a terminal window, please type the following:
```bash
python manage.py runserver
```

### Step 6: Navigate to the site
You're ready to view the website. The console should have a link to the server but if not, In your browser's URL bar, please type the following:
```bash
http://localhost:8000
```

## Authors

Contributors names and contact info

SoklyHour
[@SoklyHour](https://www.linkedin.com/in/soklyhour/)


## Acknowledgments
Inspiration, code snippets, etc.
* [django](https://docs.djangoproject.com/en/5.1/intro/)
* [bootstrap](https://getbootstrap.com/)
* [ChatGPT]()
