django-channels
===============
.. image:: https://badge.fury.io/py/django-channels.svg
   :target: https://pypi.python.org/pypi/django-channels/
   :alt: PyPI version
.. image:: https://img.shields.io/pypi/dm/django-channels.svg
   :target: https://pypi.python.org/pypi/django-channels/
   :alt: Downloads
.. image:: https://travis-ci.org/ymyzk/django-channels.svg?branch=master
   :target: https://travis-ci.org/ymyzk/django-channels
   :alt: Build Status
.. image:: https://readthedocs.org/projects/django-channels/badge/?version=latest
   :target: http://django-channels.readthedocs.org/
   :alt: Documentation Status
.. image:: https://codeclimate.com/github/ymyzk/django-channels/badges/gpa.svg
   :target: https://codeclimate.com/github/ymyzk/django-channels
   :alt: Code Climate
.. image:: https://coveralls.io/repos/ymyzk/django-channels/badge.svg?branch=master
   :target: https://coveralls.io/r/ymyzk/django-channels?branch=master
   :alt: Coverage Status
.. image:: https://requires.io/github/ymyzk/django-channels/requirements.svg?branch=master
   :target: https://requires.io/github/ymyzk/django-channels/requirements/?branch=master
   :alt: Requirements Status

django-channels is a Django library for sending notifications.
HipChat, Slack, Twitter and Yo are supported for now.

At a Glance
-----------
After installation and configuration, you can send notifications to HipChat,
Slack, Twitter, or Yo with a following simple code:

.. code-block:: python

   import channels

   channels.send("Sample notification.")

See `Quickstart`_ page for more details.

Requirements
------------

Python
^^^^^^
* Python 2.7+
* Python 3.2+
* PyPy
* PyPy3

Django
^^^^^^
* Django 1.7
* Django 1.8
* Django 1.9

Installation
------------

.. code-block:: shell

   pip install django-channels

Links
-----
* `Documentation`_
* `GitHub`_

.. _Documentation: http://django-channels.readthedocs.org/
.. _GitHub: https://github.com/ymyzk/django-channels
.. _Quickstart: http://django-channels.readthedocs.org/en/latest/quickstart.html
