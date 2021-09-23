# django-polls-tut 
This is a [basic poll application](https://docs.djangoproject.com/en/3.2/intro/tutorial01/) that lets users vote, or choose and submit answers to poll questions.  
*The app also features a django admin platform that allows the administrator log in, create users, change poll questions
and save changes.*  

Concepts learned while following this tutorial include:

- Creation of virtual environments in python
- Activation of virtual environments
- Installing django
- Starting a project with django admin
- Starting an app with manage.py
- Starting the server with manage.py
- Creating a view
- Establishing the url for a view in the two `urls.py`files
- Working with models (creating classes to describe database objects)
- Modifying the `settings.py` file to:
 1. Include newly created apps (using the app's dotted path)
 2. Changing the timezone
- Running migrations
- Running migrations with sqlmigrate just to view the sql used to generate tables
- Running migrations for new changes
- Registering a new app on `admin.py`
- create a super user and log in to the admin platform
- Interacting with the django api using `manage.py shell` to:
 1. Write records to the database
 2. Query records from the database
 3. Delete records from the database
- Create templates with HTML views
etc

To run the application: 
- cd to the outer mysite folder, `\> cd django-polls-tut/mysite`
- run `\> py manage.py runserver`,
- open a browser then go to 127.0.0.1:8000/polls.

The app is still in development and this code will be updated as new features are added.
