
|PypiVersion| |Pypi|

=======================================================
FeinCMS Extension for Responsive Theme for Django Admin
=======================================================

.. contents::
   :local:

Requirements
------------

* FeinCMS
* Django Admin Bootstrap

Installation
------------

.. code-block:: bash

    pip install bootstrap-admin-feincms

    # or latest

    pip install git+https://github.com/django-admin-bootstrap/django-admin-bootstrap-feincms.git@develop#egg=bootstrap_admin_feincms

Configuration
-------------

.. code-block:: python

    INSTALLED_APPS += ('bootstrap_admin_feincms')


.. code-block:: bash

    manage.py collectstatic --noinput

Read More
---------

* http://feincms-django-cms.readthedocs.org/en/latest/index.html
* https://github.com/django-admin-bootstrap/django-admin-bootstrap

.. |Pypi| image:: https://pypip.in/d/bootstrap-admin-feincms/badge.svg?style=flat
.. |PypiVersion| image:: https://pypip.in/version/bootstrap-admin-feincms/badge.svg?style=flat
