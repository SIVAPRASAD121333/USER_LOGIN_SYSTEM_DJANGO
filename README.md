# USER_LOGIN_SYSTEM_DJANGO
User will be able to Register in the website. User will receive a confirmation email in order to activate their account.

Abstract:

-	User will be able to Register in the website.
-	User will receive a confirmation email in order to activate their account.
Requirements:
-	Device (Laptop or Desktop) should have python installed it. (If not, download and install python from: 
https://www.python.org/downloads/ ) 
-	Don’t forget to add ‘python’ to the PATH in your environment Variables. (Refer: https://www.geeksforgeeks.org/how-to-add-python-to-windows-path/ )

Steps: 
-	Install virtual environment for comfort (optional but recommended)
-	Create Django Project 
-	Create Django App 
-	Start with the development

Commands: 
-	Install virtual environment: ‘pip install virtualenv’ 
-	Create a virtual environment: ‘virtualenv venv (name_of_venv)’
- Activate virtual environment:
    - Windows: ‘venv\Scripts\activate’
    - Mac OS/Linux: ‘source venv/bin/activate’ 
- Install Django: ‘pip install django’
- Create a Django Project:‘django-admin startproject project_name’  
- Create a Django App: ‘python manage.py startapp app_name’
- Create a Superuser (admin): ‘python manage.py createsuperuser’ 

Create a Dashboard View:

Strcucture of the Project:

USER_LOGIN_SYSTEM_DJANGO-main/
│
├──> authentication/
|   ├──> _pycache_
|   |──> migrations
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── tokens.py
│   ├── urls.py
│   └── views.py
│
├──> templates/
│   │
│   ├──> authentication/  
│   |     ├── index.html
|   |     ├── signin.html
│   │     └──signup.html
│   ├──¬¬¬¬¬ activation_failed.html
│   └── email_confirmation.html

├──> user_login/   
|   ├──> _pycache_
│   ├── __init__.py
│   ├── asgi.py
│   ├── info.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   ├── urls.py
│   └── views.py
│
├── db.sqlite3
└── manage.py

For Complete Code:
https://github.com/SIVAPRASAD121333/USER_LOGIN_SYSTEM_DJANGO

Step1: Run the server in Terminal: "python manage.py runserver" 

Create Super user first, After successfully RUN THE CODE i.e., "python manage.py createsuperuser", Enter Username, Email, Password

Step2: Run the server Again: "python manage.py runserver"

Step3: Run on Tab: http://127.0.0.1:8000/ (Signup, Signin and Signout)

Step4: RUN THE BELOW i.e., ADD: "admin" and login with username and password (using "username" and "password" that are created after 
       Creating Superuser in Step1), run below http://127.0.0.1:8000/admin and after login with credentials of superuser,
       Check the all the users list.

