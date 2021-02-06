# Blog API

## This is the Django project, which can provide APIs for commercial usage. 

You can:
* Add and remove users
* Create, delete and edit blogs
* Use API for your own web-app, mobile application or for any other aims

## Installing
### Run in your Terminal ```python manage.py runserver```
### If there is an error just make following steps:
* Run ```pipenv install django```
* ```pipenv shell```
* ```python manage.py migrate```
* ```python manage.py runserver```

## After the application is successfully run, you can reach the site by typing in your browser ```127.0.0.1:8000``` or ```localhost:8000```
### And there are some routes:
* ```/api/v1``` Main page with the list of all blogs
* ```/docs/``` Blog API documentation

## Main features:
* User authorization
* Editing restriction (allowed for author only)
* User-friendly documentation and schema
* Token auth
