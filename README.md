# First_django
#instructions
1.Install django through pip by writing "pip install django"
2.Start a django project by typing "django-admin startproject 'projectname' "
3.Start a app by typing "python3 manage.py startapp 'appname'"
4.Go to views.py file in app ,import class HttpResponse from django.htttp
5.Create a index function which takes request as an argument and returns HttpResponse("Hello world")
6.To add this to ur site  go to the urls.py in ur main app,import views.py from the app
7.Add 'path("",views.index)' to the urlpattern list 
8.Type 'python3 manage.py runserver' to start ur site at http://127.0.0.1:8000/ 
