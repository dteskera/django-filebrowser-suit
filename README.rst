Django FileBrowser
==================

**Media-Management**. (based on https://github.com/sehmaschine/django-filebrowser)

The FileBrowser is an extension to the `Django <http://www.djangoproject.com>`_ administration interface in order to:

* browse directories on your server and upload/delete/edit/rename files.
* include images/documents to your models/database using the ``FileBrowseField``.
* select images/documents with TinyMCE. (v4)

Requirements
------------

FileBrowser 3.5 requires

* Django 1.4/1.5/1.6/1.7 (http://www.djangoproject.com)
* Pillow (https://github.com/python-imaging/Pillow)

No Grappelli
------------

This fork removes the dependency on Grappelli.

.. figure:: docs/_static/Screenshot.png
   :scale: 50 %
   :alt: django filebrowser no grappelli

Django Suit
-----------

This fork is tweaked for using with django-suit



Installation
------------

    pip install -e git+git://github.com/dteskera/django-filebrowser-suit.git#egg=django-filebrowser

Documentation
-------------

http://readthedocs.org/docs/django-filebrowser/

It also has fake model to show filebrowser in admin dashboard, but you can disable it by setting ``FILEBROWSER_SHOW_IN_DASHBOARD = False``.

Translation
-----------

https://www.transifex.com/projects/p/django-filebrowser/

Releases
--------

* FileBrowser 3.5.8 (Development Version, not yet released, see Branch Stable/3.5.x)
* FileBrowser 3.5.7 (September 10th, 2014): Compatible with Django 1.4/1.5/1.6/1.7

Older versions are availabe at GitHub, but are not supported anymore.
