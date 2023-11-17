# DJANGO INTRO
Check if you have python installed and which version
```bash
python --version
```
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
```
pipenv shell
```
Make sure python_version is set to a version that is 3 or greater. If the version mentioned in the Pipfile is already 3 or greater, then you can skip to the next step (i.e., install django).
```
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