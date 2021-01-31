=====
Morpholy
=====

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "morpholy" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'morpholy',
    ]

2. Include the polls URLconf in your project urls.py like this::

    path('morpholy/', include('morpholy.urls')),

3. Run ``python manage.py migrate`` to create the polls models.
