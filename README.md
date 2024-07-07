# django-job-project


app create>> == app install

AbstractUser>>
from django.contrib.auth.models import AbstractUser
class CustomUser(AbstractUser):
	pass
AUTH_USER_MODEL='jobApp.CustomUser'
1) py manage.py makemigrations jobApp
2) py manage.py migrate jobApp
3) py manage.py migrate
4) py manage.py createsuperuser
5) py manage.py runserver
