# medical-scanner-py
Medical inventory management using python (Quick Stock Management System for Medical Purpose)

---------------------

Prerequisites:
Install Python
Setup mysql on locahost and port 3306
Create Database with name 'medicalscannar'

---------------------

How To Run Project:

A. Run BackEnd
1. Navitage to /medical-scanner-py/medical-scanner-py folder and open command prompt in it
2. Enter command: Scripts/activate
3. Enter command: pip install -r requirements.txt
4. Enter command: python manage.py makemigrations 
5. Enter command: python manage.py migrate
6. Enter command: python manage.py runserver 0.0.0.0:8000

This will start back end application on localhost:8000

---------------------

B. run Front end(UI)
1. Navigate to /UI folder and open command promt in it
2. Enter command: python -m http.server 9000

This will start front end on localhost:9000


---------------------

Now open any browser and visit localhost:9000

Application will start.
1.Register new user on registration page
2.Insert some items in database from backend(using sql query on database) 
3.Install Medscanner Android app
4.Login to Android app with same credentials used to login web App.
You are ready to go.