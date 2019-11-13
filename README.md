# ubu-datascience-webapp

## install pipenv

...sh
python -m pip install pipenv --user


##install django
...sh
pipenv install django

## start pipenv
...sh
pipenv shell
...

# start django web project

...sh
django-admin startproject webapp
cd webapp
python manage.py startapp myapp
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

