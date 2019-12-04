# First_django
#instructions
>Install django through pip by writing "pip install django"
>Start a django project by typing "django-admin startproject 'projectname' "
>Start a app by typing "python3 manage.py startapp 'appname'"
>Go to views.py file in app ,import class HttpResponse from django.htttp
>Create a index function which takes request as an argument and returns HttpResponse("Hello world")
>To add this to ur site  go to the urls.py in ur main app,import views.py from the app
>Add 'path("",views.index)' to the urlpattern list 
>Type 'python3 manage.py runserver' to start ur site at http://127.0.0.1:8000/ 
