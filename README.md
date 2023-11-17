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