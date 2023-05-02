# Django Girls tutorial de blog

> Este sitio es el resultado final del [Tutotrial Django Girls](https://tutorial.djangogirls.org/).

Dependencias:

*   Python 3.6
*   Django 1.11
*   Wagtail 2.0

## Para poder correr el programa correr:

```sh
git clone git@github.com:elizabethygonz/my-first-blog.git
cd my-first-blog
python3.6 -m venv myvenv
source myvenv/bin/activate
pip install --upgrade pip
pip install django~=1.11.0
python manage.py migrate
python manage.py runserver
```

## Sobre Django, Wagtail

http://docs.wagtail.io/en/v2.0.1/getting_started/integrating_into_django.html

```sh
source myvenv/bin/activate
pip install wagtail~=2.0.0
python manage.py migrate
python manage.py runserver
```

### PythonAnywhere

```
cd ~/elizabethygonz.pythonanywhere.com
workon elizabethygonz.pythonanywhere.com
python manage.py collectstatic
```
