# MongoDB Django Quickstart

A small Django project that connects to MongoDB Atlas using `django-mongodb-backend`.  
The app uses MongoDB's `sample_mflix` database and displays movie and viewer data through simple Django views.

## Features

- Django 6 project setup
- MongoDB Atlas connection using `django-mongodb-backend`
- Reads data from the `sample_mflix` database
- Displays:
  - Five most recent movies
  - Viewers list sorted alphabetically
- Uses MongoDB collections through Django models

## Tech Stack

- Python 3.12
- Django 6.0.6
- django-mongodb-backend 6.0.3
- PyMongo
- MongoDB Atlas


**Setup:** 
- Clone the repo with `git clone <your-repository-url>`
- enter the folder with `cd <project-folder>`
- create a virtual environment using `python -m venv env`
- activate it with `.\env\Scripts\Activate.ps1` on Windows or `source env/bin/activate` on macOS/Linux
- install dependencies with `pip install -r requirements.txt` or `pip install Django django-mongodb-backend pymongo dnspython`
- add your MongoDB Atlas connection string in `quickstart/quickstart/settings.py`
- move into the Django folder with `cd quickstart`
- run migrations using `python manage.py migrate`
- start the server with `python manage.py runserver`
- then open **http://127.0.0.1:8000/** in your browser
