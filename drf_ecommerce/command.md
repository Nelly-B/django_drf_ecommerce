#packages


django
python-dotenv0.21.0
djangorestframwork
pytest


#commands
django-admin startproject drf_ecommerce
./manage.py runserver

#To obtain secret key
from django.core.management.utils import get_random_secret_key 
print(get_random_secret_key())

#To run test
python -m unittest test_example.py