[//]: # ({% comment "This weird comment is a hacky way to provide both a README for the template and a template for the README. Markdown will ignore this and Django's templating will ignore everything until the matching endcomment tag." %})
mySociety's Django app template
===============================

This is a template for creating Django apps (using [Django's facility for
such](https://docs.djangoproject.com/en/1.9/ref/django-admin/#cmdoption-startapp--template))
in a mySociety-ish way. It's probably not all that useful to you unless you
are a mySociety developer, or are interested in how we do things.

Usage
-----
Assuming you already have a Django project setup and running, just run the
following from within your virtualenv (replace app_name with what you'd like
your app to be called):

```
$ ./manage.py startapp --extensions md --template=https://github.com/mysociety/django-app-template/archive/master.zip app_name
```

See also
--------
We have a similar template for creating whole new Django projects:
https://github.com/mysociety/django-project-template

README Generation
-----------------

The following Django template will be used to generate a basic README for your
app - you can probably delete it if you don't want a separate README.

[//]: # ({% endcomment %}you can delete this line, it's a hack from the app template)
{{ app_name|capfirst }}
===========================

Put a top-level description of your app here.
