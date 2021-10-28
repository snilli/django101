# Django 
develop with Don’t repeat yourself (DRY) 
polls module
```
Every distinct concept and/or piece of data should live in one, and only one, place. Redundancy is bad. Normalization is good.

The framework, within reason, should deduce as much as possible from as little as possible.
```
and module base can be reuse anywhere


Topic to learn

- [x] Sub module
- [x] Routing path
- [x] Database seting
- [x] Model 
  - [x] Implement 
  - [x] Manage with admin ui
  - [x] Migratate command 
- [x] Views 
  - [x] Implement 
  - [x] Mapping with url 
  - [x] Intregate with model
  - [x] Form handle
  - [x] Generic views 
  - [x] Static file
- [x] Form Model

CMD
```
create new app
django-admin startproject --app name

python manage.py makemigrations ## optional --app name 

python manage.py migrate

python manage.py runserver
```

Interasing
- race condition F()

# Django rest framework
snippets module
Topic to learn 

- [x] Serialization Model
- [x] Requests and Responses for rest api
- [x] Implement view with class base