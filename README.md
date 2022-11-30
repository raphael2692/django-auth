# django-auth


Basic django DRF API with jwt token and admin panel configured to be used by other apps. 

I clone/fork this repo for testing/prototyping pourposes. 

```

git clone
cd djangoauth
# activate venv
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser --email admin@example.com --username admin
python manage.py runserver

```