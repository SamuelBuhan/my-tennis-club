#

Tutorial on how to use Django, for more information visit https://www.w3schools.com/django/django_create_project.php

## Installation
```
$ python3 -m pip install django
```

To check if Django is well install use:

```
$ django-admin --version
```

It should return the version of Django.

## Start a project 
Use this command to start a project

```
$ django-admin startproject my_tennis_club
```
It creates a folder *my_tennis_club* in the folder with basic template of Django.

## Run server
Use this command to run the server locally at http://127.0.0.1:8000/

```
$ python3 my_tennis_club/manager.py runserver
```

The URL display a basic Django website.

## Create app

App is a web application that as a specific purpose in the project.

```
$ python3 manage.py startapp members
```

### View 
View are the response to an http request and they can be configure in *views.py*.

### URLS
Todo

### Model
Todo

### Migration
Allowed to create a table of the model in the database

```
$ python3 manage.py makemigrations members
```

It creates a file named * members\migrations\0001_initial.py*. 
Now *Members* is added in database 
