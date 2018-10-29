=====
django-audit
=====

django-audit is a simple Django app to create auditable fields in django models.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "auditable" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'auditable',
    ]

2. Run `python manage.py migrate` to create the polls models.

