### A Minimal Flask Project skeleton

#### Includes:
- [Flask]
- [Docker]
- [Boostwatch] [Flatly]

#### Usage:
```sh
$ pip install cookiecutter
$ cookiecutter https://github.com/fastfuse/cookiecutter-flask-minimal.git
```

You will be asked about basic info (app name, description).
This info will be used in your new project.

Create and activate virtual environment

After that:

```sh
$ cd <your-newly-created-project>
$ export APP_SETTINGS=config.DevelopmentConfig
$ export FLASK_APP=app/__init__.py
$ export FLASK_ENV=development
$ flask run
```

Or using Docker:
```sh
$ cd <your-newly-created-project>
$ docker build . -t <image-name>
$ docker run -it -p 5000:5000 <image-name>
```

Open your browser and check [127.0.0.1:5000]

[Flask]: http://flask.pocoo.org/
[Docker]: https://www.docker.com/
[Boostwatch]: https://bootswatch.com/
[Flatly]: https://bootswatch.com/flatly/