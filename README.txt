# Simple-Login-Template-Django
The following is a sample signup/login template that utilizes HTML files for the frontend and Python Django for a framework and language.
To test out the following create a virtual environment using the following:
C:\Users\Owner> cd desktop

C:\Users\Owner\desktop> py -m venv env

C:\Users\Owner\desktop> cd env

C:\Users\Owner\desktop\env> Scripts\activate

(env)C:\Users\Owner\desktop\env>

After creating the virtual environment and activating it make sure to have downloaded and installed Django:
(env)C:\Users\Owner\desktop\env> pip install django==2.1.15
Afterthat, pip install the required libraries found in the requirements.txt file
Run the server after making migrations in the project and placing it in the env folder
(env)C:\Users\Owner\desktop\env>cd mysite
(env)C:\Users\Owner\desktop\env\mysite>python manage.py migrate
(env)C:\Users\Owner\desktop\env\mysite>python manage.py runserver
After running the server check local host at port 8000 (link:http://127.0.0.1:8000/)
Access the site and test it freely
