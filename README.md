#This is a Working backend Django model for JWT Authentication.
To use this follow the steps below->
```bash
-------------------------------------------------------------
py -m pip install --user virtualenv
-------------------------------------------------------------
py -m venv <yourenvironmenttname>
-------------------------------------------------------------
in windows type
.\<yourenvironmentname>\Scripts\activate
in linux type 
source ./myproject/bin/activate
-------------------------------------------------------------
pip install -r requirements.txt
-------------------------------------------------------------
python manage.py makemigrations
-------------------------------------------------------------
python manage.py migrate
-------------------------------------------------------------
Make a .env file and add {EMAIL_USER = 'contact@gmail.com',EMAIL_PASS = 'qwerty',EMAIL_FROM = 'contact@gmail.com.com'} these fields.
-------------------------------------------------------------
python manage.py runserver
```
