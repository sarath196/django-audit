=====
django-audit
=====

django-audit is a simple Django app to create reusable audit fields in django models.

1. created_on
2. created_by
3. modified_on
4. modified_by

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "auditable" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'auditable',
    ]
2. Import audit app and inherit to your custom models.

2. Run `python manage.py migrate` to create audit fields.

