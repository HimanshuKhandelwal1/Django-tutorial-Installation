# Django tutorial for Installation in windows for python 3
If you are new for django than lets have some information guide. Guide means not the solution but what is django? So lets start....

## Django
Django is a Web framework written in Python. It is a software that supports 
 - the development of dynamic Web sites, applications, and services. 
 - security features, 
 - database access, 
 - sessions, 
 - template processing, 
 - URL routing, 
 - internationalization, 
 - localization, and much more.

Django enables you to develop secure and reliable Web applications very quickly in a standardized way, without any delay.

## Why Django is soo speacial?
any Idea no,.... than no problem,
For starters, it’s a Python Web framework, and as you know, python is having a wide of range of open source libraries. It hosts over 116K packages (till Sep. 2017). If you need to solve a specific problem, the chances are someone has already implemented a library for it.

Django is one of the most popular Web frameworks written in Python. It is complete and offering a wide range of features such as 
 - a standalone Web server for development and testing, 
 - caching, 
 - middleware system, 
 - ORM, 
 - template engine, 
 - form processing, 
 - interface with Python’s unit testing tools. 
It also comes with the built-in applications such as 
 - authentication system, 
 - an administrative interface with automatically generated pages for CRUD operations, 
 - generation of syndication feeds (RSS/Atom), sitemaps. 
 - Geographic Information System (GIS) framework.
The development of Django is sponsored by companies like JetBrains and Instagram.
It is good to know that Django is used by biggest Web sites such as 
 - Instagram, 
 - Disqus, 
 - Mozilla, 
 - Bitbucket, 
 - Last.fm, 
 - National Geographic.

### Initial Installation required for Django
For to ply with django, you have to install some programs in you machine.
 1. Python 2 / 3 (it depends on you but i preferred python3 because it is update one and most of the functionality of Django work in python3)

 2. Virtual Environment for the Django project.

####Python Installation
You can download the python from the python official site https://www.python.org/downloads/ here and keep on clicking next.
For, running the python from command prompt, you have to set the path for the python3 in environment variable for your system in windows.
now you can run the python by command prompt and navigate to the folder of your Python project or where you want to create the Django project.

#### Virtual Environment setup
For Django, you need virtual environment in python. Now, you are thinking why and what is virtual environment in python?
Python allow you to create a isolated working copy of the python which allow you to work on any project without affecting the other projects environment and also enables side by side installation of python for every project.
Virtual Environment is necessary for the Django project so that to avoid any type of conflict between multiple django projects.

Pip command for virtual environment creation is(PIP is a tool for manage and install python packages. 
### pip install virtualenv

now create a folder for the your django files and folders.
### mkdir <foldername>
  
now create the virtual environment for your first django project.
### virtualenv <environment name>

Now activate the virtual environment for the django installation.
### <environment name>/Scripts/activate (in command prompt.)
  
you can check that the virtual environment is activate by seeing the command prompr that you environment name is like this 
###(environment name) c:/user/projects/(ur folder name)

Now install the Django in this environment and it will be available for this environment only.
### pip install django

###Starting a New Project in Django

To start a new Django project, we have to run a command:
### django-admin startproject myproject

The command-line utility django-admin is automatically installed with Django. After we run the command above, it will generate the base folder structure for a Django project. The initial project structure is composed of five files:
#### manage.py: 
a shortcut to use the django-admin command-line utility. It’s used to run management commands related to our project. We will use it to run the development server, run tests, create migrations and much more.
#### __init__.py: 
this empty file tells Python that this folder is a Python package.
#### settings.py: 
this file contains all the project’s configuration. We will refer to this file all the time!
#### urls.py: 
this file is responsible for mapping the routes and paths in our project. For example, if you want to show something in the URL /about/, you have to map it here first.
#### wsgi.py: 
this file is a simple gateway interface used for deployment. You don’t have to bother about it. Just let it be for now.

### Run web server for confirmation
Django comes with a simple web server installed. It’s very convenient during the development, so we don’t have to install anything else to run the project locally. We can test it by executing the command:
### python manage.py runserver

Ignore all the warning and check in your browser by the following URL in a Web browser: 
### http://127.0.0.1:8000 

and you should see the following page:


