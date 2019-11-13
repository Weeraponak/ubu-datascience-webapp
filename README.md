# ubu-datascience-webapp
<<<<<<< HEAD

## install pipenv

...sh
python -m pip install pipenv --user


##install django
...sh
pipenv install django

=======
## install pipenv
...sh
python -m pip install pipenv --user
##install django
...sh
pipenv install django
>>>>>>> 4cd9bb0a4e47e78f03ae435fcb0bd86ec542b200
## start pipenv
...sh
pipenv shell
...
<<<<<<< HEAD

# start django web project

=======
# start django web project
>>>>>>> 4cd9bb0a4e47e78f03ae435fcb0bd86ec542b200
...sh
django-admin startproject webapp
cd webapp
python manage.py startapp myapp
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

