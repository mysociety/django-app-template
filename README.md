This is a template for creating Django apps (using [Django's facility for
such](https://docs.djangoproject.com/en/1.9/ref/django-admin/#cmdoption-startapp--template))
in a mySociety-ish way. It's probably not all that useful to you unless you
are a mySociety developer, or are interested in how we do things.

Usage
-----
Assuming you already have a Django project setup and running, just run the
following from within your virtualenv (replace app_name with what you'd like
your app to be called):

    ./manage.py startapp --template=https://github.com/mysociety/django-app-template/archive/master.zip app_name

See also
--------
We have a similar template for creating whole new Django projects:
https://github.com/mysociety/django-project-template
