# Introduction to django
Check if you have python installed and which version
```bash
python --version
```
Make sure python_version is set to a version that is 3 or greater.

Check if you have `pip` and which version
```bash
pip --version 
```
```bash
 pip3 --version
```
If you don't have `pipenv` installed
```bash
brew install pipenv
```

## Inside Pip
switch to `pip` environment
```bash
pipenv shell
```
install latest version of django inside `pipenv`
```bash
pipenv install django
```

Next, we're going to install the library for connecting Django to PostgreSQL:
```bash
pipenv install psycopg2-binary

```
All we've done so far is install our dependencies and create our virtual environment. Now, we want to start our Django project:

```bash
django-admin startproject django_demo .
```

to start the project
```bash
python3 manage.py runserver
```

to create an app(should be in the same level as manage.py)
```bash
python3 manage.py startapp demo_app1
```

## Readings
### About the files in the project
#### apps.py
The apps file controls settings specific to this app.
We won't need to edit this for our project, and it is pretty rare to do so.
#### models.py
The models file provides the data layer, which Django uses to construct our database schema and queries. 
#### admin.py
The admin file defines an administrative interface for the app that will allow us to see and edit the data related to this app.
#### urls.py
The urls file can be used for URL routing specific to this app.
#### views.py
The views file defines the logic and control flow for handling requests and defines the HTTP responses that are returned.
#### tests.py
The tests file can be used for writing unit tests for the functionality of this app. 
#### migrations folder
the migrations folder holds files which Django uses to migrate the database as we create and change our database schema over time.