# flaskr

Simple Flask App

## Starting the app

Optional step: create a virtual environment first, and activate it.

Install all required Python packages. Must be run in top level `flaskr/`
directory:
```
pip install --editable .
```

Make sure the DB is initialized:
```
export FLASK_APP=flaskr
export FLASK_DEBUG=true
flask initdb
```

Start the actual web application on port 5000:
```
export FLASK_APP=flaskr
export FLASK_DEBUG=true
flask run
```

Run automated tests:

```
python setup.py test
```
