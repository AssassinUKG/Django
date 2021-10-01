# Django
Simple setup/overview

## Install

```
pip3 install Django==2.2.12
```

## Crate a project

```
mkdir website_files
# Starts a new project called appone (rename etc)
django-admin startproject appone
# Configures new files
python3 manage.py migrate
```

## Utility

Basic syntax for using this utility is ```python3 manage.py {command}```

## Run

To run a server, type

```
python3 manage.py runserver
```

## Localhost

Any access issues, open settings.py located in the website files. Add address to ```ALLOWED_HOSTS```

```
ALLOWED_HOSTS = ['0.0.0.0','127.0.0.1']
```

# Create a super user. 

Allows you to create a super user (admin) for IP:8000/admin login page. 

```
python3 manage.py createsuperuser
```

## Start

Startapp allows you to initialize an app for your project. Django projects can have an infinte numer of apps. 


```
python3 manage.py startapp {app_name}
```
