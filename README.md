
```bash
py -m pip install --user virtualenv
py -m venv <yourenvironmenttname>
.\<yourenvironmentname>\Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
Make a .env file and add {EMAIL_USER = 'contact@gmail.com',EMAIL_PASS = 'qwerty',EMAIL_FROM = 'contact@gmail.com.com'} these fields.
python manage.py runserver
```
