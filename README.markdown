====================
NO LONGER MAINTAINED
====================
Since master branch is now mantained this one will not be anymore 

please use this: https://github.com/charettes/django-colorful


twentytab-colorful
================

It's a fork of "django-colorful"

**django-colorful** is an extension to the Django web framework that provides
database and form color fields (only RGB atm).

Written by Simon Charette
Inspired by http://djangosnippets.org/snippets/1261/
Built with https://github.com/laktek/really-simple-color-picker

Usage
-------------
In order to use a color field you just have to add it to your model definition:

    from django.db import models
    from colorful.fields import RGBColorField

    class Tag(models.Model)
      color = RGBColorField()

The extension will take care of providing the custom widget, just make sure you
include the static files and jQuery >= 1.6.

In order to use with django.contrib.staticfiles add 'colorful' to
project's INSTALLED_APPS.
