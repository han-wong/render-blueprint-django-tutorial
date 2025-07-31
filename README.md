# Python project

## Create a virtual environment
- python -m venv venv

## Activate virtual environment
- .\venv\Scripts\activate

## Update pip in virtual environment
- python -m pip install --upgrade pip

## Install packages in virtual environment
- python -m pip install -r .\requirements.txt

## Create a Django project
- python manage.py startapp mysite

## Run Django server
- python manage.py runserver