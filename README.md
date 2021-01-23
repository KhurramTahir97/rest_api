# rest_api
Django Rest Framework Api Test

Steps for setup project :

1) Create VirtualEnvironment ___________________  python3 -m virtualenv environment_name

2) Activate VirtualEnvironment _________________ source bin/activate (inside virtual enviroment folder)

3) Now On Main python project outside apis app there's a file requiremnts.txt _________________ pip install -r requirements.txt
   It will install all required libraries to run project.
   
4) Now Open settings.py in main project and configure database ______________________ 
   
   DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'Your_DB_NAME',
        'USER': 'YOUR_DB_USER',
        'PASSWORD': 'YOUR_DB_PASS',
        'HOST': 'YOUR_HOST',
        'PORT': 'YOUR_PORT',
    }
}

5) Now CreateUser for accessing admin panel ___________ python manage.py createsuperuser
   and provide username,password,email etc.

6) now apply migrations ____________ python manage.py migrate 
   it will create all required db tables in your DB.

7) Finally now run project ________________ python manage.py runserver

 
