# django-job-project


**app create use: app install **
'appname'
<hr>
** AbstractUser use: **
from django.contrib.auth.models import AbstractUser <br>
class CustomUser(AbstractUser):
	pass
AUTH_USER_MODEL='jobApp.CustomUser'
1) py manage.py makemigrations jobApp
2) py manage.py migrate jobApp
3) py manage.py migrate
4) py manage.py createsuperuser
5) py manage.py runserver



**login_required use:**
from django.contrib.auth import authenticate,login,logout <br>
@login_required
def view_function(request):
    pass
```
