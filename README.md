# Django Girls tutorial blog

> This site is the end result of the [Django Girls tutorial](https://tutorial.djangogirls.org/).

Dependencies:

*   Python 3.6
*   Django 1.11
*   Wagtail 2.0

To get this project up and running,

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

## Beyond Django, Wagtail

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
