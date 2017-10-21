A Minimal Flask Project skeleton
================================
Includes:
---------

- Flask
- Flask-Script
- Boostwatch_ Flatly_ (Bootstrap3 theme)
- `Font Awesome <http://fontawesome.io/>`_

.. _Boostwatch: https://bootswatch.com/
.. _Flatly: https://bootswatch.com/flatly/
Usage:
------
::

    $ pip install cookiecutter
    $ cookiecutter https://github.com/fastfuse/cookiecutter-flask-minimal.git
You will be asked about basic info (app name, description). This info will be used in your new project.
After that:
-----------
::

    $ cd <your newly created project>
    $ pip install -r requirements.txt
    $ export APP_SETTINGS="config.DevelopmentConfig"
    $ python manage.py runserver
