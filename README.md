# The purpose of this project is to learn how to create a Django web app
## The source of learning is from https://tutorial.djangogirls.org/en/

# Commands To Start Django App

## Create Virtual Environment
``` python -m venv myvenv ```

## Start Virtual Environment, Run this before doing anything
``` source myvenv/bin/activate ```

## Upgrade pip
``` python -m pip install --upgrade pip ```

## Create requirements.txt (this is kinda like package.json) and install
``` touch requirements.txt && pip install -r requirements.txt  ```

## Start the project, this will create manage.py and etc.
``` django-admin startproject <project name> . ```

## Migrate
``` python manage.py migrate ```

## To Start Server
``` python manage.py runserver ```

## Create the Application
``` python manage.py startapp <app name> ```

## After creating your model
``` python manage.py makemigrations <app name>```

## Run the migration
``` python manage.py migrate <app name> ```

## Create super user to login at /admin
```python manage.py createsuperuser```

## Open Django shell
```python manage.py shell```