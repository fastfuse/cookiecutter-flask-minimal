FROM python:3.6-slim

RUN echo 'Dockerfile-Application'

RUN mkdir /app
WORKDIR /app
COPY . /app
RUN pip install --no-cache-dir -r requirements.txt

# environment variales
ENV FLASK_APP="app/__init__.py"
ENV FLASK_DEBUG=1
ENV APP_SETTINGS="config.DevelopmentConfig"

# expose port
EXPOSE 5000

# run
ENTRYPOINT flask run --host=0.0.0.0