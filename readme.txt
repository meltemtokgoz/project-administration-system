-We used django as web aplication frameworks
-We used PostgreSQL for storing the our data
-Version of PostgreSQL == postgresql-11.1-1-windows-x64
-What should be installed requirements:
	-pip install django==1.10
	-pip install psycopg2
	-pip install django-crispy-forms==1.6.1
	-pip install django-ckeditor
	-python manage.py collectstatic
	-python manage.py runserver
-We used Bootstrap(Bootstrap is an open source a front-end framework)
-We used Crispy Form in our project for form.html design
-We have 3 type user[
	-admin
	-customer
	-company
	]
-User must be own type to type part in log in page
-We have home page for every user and they redirect according to their type
-While an admin is creating a new user, he/she clicked create user and his redirecting to admin page in django administration.
