### A Minimal Flask Project skeleton

#### Includes:
- [Flask]
- [Docker]
- [Boostwatch] [Flatly]

#### Usage:
Copy flask-min dir and rename it

Create and activate virtual environment

After that:

```sh
$ cd <your-project-dir>
$ export APP_SETTINGS=config.DevelopmentConfig
$ export FLASK_APP=app/__init__.py
$ export FLASK_ENV=development

$ flask db init
$ flask db migrate -m "<migrate message>"
$ flask db upgrade

$ flask run
```

Open your browser and check [127.0.0.1:5000]

[Flask]: http://flask.pocoo.org/
[Docker]: https://www.docker.com/
[Boostwatch]: https://bootswatch.com/
[Flatly]: https://bootswatch.com/flatly/
[127.0.0.1:5000]: http://127.0.0.1:5000