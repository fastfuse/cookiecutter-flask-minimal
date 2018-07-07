### A Minimal Flask Project skeleton

#### Includes:
- [Flask]
- [Docker]
- [Boostwatch] [Flatly]
- [Font Awesome]

#### Usage:
```sh
$ pip install cookiecutter
$ cookiecutter https://github.com/fastfuse/cookiecutter-flask-minimal.git
```

You will be asked about basic info (app name, description).
This info will be used in your new project.

After that:

```sh
$ cd <your-newly-created-project>
$ docker build . -t <image-name>
$ docker run -it -p 5000:5000 <image-name>
```

[Flask]: http://flask.pocoo.org/
[Docker]: https://www.docker.com/
[Boostwatch]: https://bootswatch.com/
[Flatly]: https://bootswatch.com/flatly/
[Font Awesome]: http://fontawesome.io/