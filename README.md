This is what i got following [django tutorial](https://docs.djangoproject.com/fr/1.11/intro/tutorial01/) and [django rest quickstart](https://django-rest-framework-old-docs.readthedocs.io/en/3.7.7/tutorial/quickstart/)

I used here `Django 1.11` and `djangorestframework 3.7.1` and Python 3.4

To start the app run this commands in the top `mysite` directory:
- `python3 manage.py runserver`
 
 You can test it on your web browser at:
  - http://localhost:8000/users/ or http://127.0.0.1:8000/users/ for the API
  - http://localhost:8000/polls/ or http://127.0.0.1:8000/polls/ for my django polls app
  - http://localhost:8000/admin/ or http://127.0.0.1:8000/admin/ for administrate my django app (you need to go here to create new questions or manage existing ones)
  
  The admin name is `admin` and the password is `uncommon` but I recommend you to follow the django tutorial and make your own database
