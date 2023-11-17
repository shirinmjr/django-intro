# DJANGO INTRO
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
install django
add the latest version after `==`
```bash
pip3 install django==3.1.1
```
switch to `pip` environment
```bash
pipenv shell
```
install django inside `pipenv`
```bash
pipenv install django
```

Next, we're going to install the library for connecting Django to PostgreSQL:
```bash
pipenv install psycopg2-binary

```
All we've done so far is install our dependencies and create our virtual environment. Now, we want to start our Django project:

```bash
pipenv run django-admin startproject tunr_django .
```

```django-admin startproject smartmotes .```