# x-cork-a-flask
Cork a flask

## Start it up

From within Anaconda

```
FLASK_APP=flask_app.py flask run
```

## Deploy

1. `heroku login`

1. `heroku create`

1. Make the following `Procfile`

```
web: flask run
```

1. `heroku config:set FLASK_APP=flask_app.py`

## Requirements whack a mole

```
git ct -a -m 'ksdjflkj' ; git ph heroku master
```
