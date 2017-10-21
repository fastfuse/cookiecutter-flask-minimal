### A Minimal Flask Project skeleton

Includes:
* Flask
* Flask-Script
* Boostwatch Flatly (Bootstrap3 theme)
* Font Awesome

Usage:
```sh
$ pip install cookiecutter
$ cookiecutter github
```

After that:
```sh
$ cd <your newly created project>
$ pip install -r requirements.txt
$ export APP_SETTINGS="config.DevelopmentConfig"
$ python manage.py runserver
```
