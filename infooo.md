## Run ##
```bash
pip install django-crispy-forms
```
```bash
pip install crispy-bootstrap4
```
```bash
pip install django-allauth
```
```bash
pip install stripe
```

1. And add crispy_bootstrap4 to the list of INSTALLED_APPS.

2. make sure to install django-environ instead of environ

3. create .env file next to the settings.py

    ### Generate the secret key with the steps below: ###
    
        1. > py manage.py shell 
        2. >>>> from django.core.management.utils import get_random_secret_key  
        3. >>>> print(get_random_secret_key())

    ### Steps ###

    1. Update the settings to connect with you database

    2. py manage.py migrate

    3. py manage.py createsuperuser

    4. py manage.py runserver

