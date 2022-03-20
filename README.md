# DjangoTodoApp
Second test Django REST Framework app.

-> To create work directory, you should write this in console:

+ mkdir **todo** && cd **todo**
+ mkdir **backend** && cd **backend**
+ pipenv install django (or conda install django)
+ pipenv shell (or conda install shell)
+ django-admin startproject config .
+ python manage.py startapp **todos**
+ python manage.py migrate
+ add to INSTALLED_APPS new app.

-> To run the server:

+ python manage.py runserver

-> To migrate the database:

+ python manage.py makemigrations **todos**
+ python manage.py migrate

-> To create superuser to log in to the admin:

+ python manage.py createsuperuser
