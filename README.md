python -m venv ll_env
ll_env/Scripts/activate
pip install django
django-admin startproject project .
python manage.py migrate

python manage.py startapp xxx
python manage.py createsuperuser
python manage.py makemigrations xxx
python manage.py migrate
