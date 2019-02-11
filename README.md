# Seperating settings.py

### setting environment variable
~~~bash
# in test environment
$ export DJANGO_SETTINGS_MODULE=django_example.settings.test
# in product enviroment
$ export DJANGO_SETTINGS_MODULE=django_example.settings.product
~~~

### run server
~~~
$ python manage.py runserver 0.0.0.0:8000
~~~