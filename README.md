# Cookiecutter Flask API Starter

This is a minimal Falsk project for bootstraping APIs. It makes of [Flask-Restplus](https://github.com/noirbizarre/flask-restplus) 
and [Flask-Sqlalchemy](https://github.com/pallets/flask-sqlalchemy) to set up a production ready API. [Gevent](https://github.com/gevent/gevent)
has also been added to handle IO based operations.

## Usage

Install [cookiecutter](https://github.com/audreyr/cookiecutter):

    pip install --user cookiecutter

Create your application from this template:

    cookiecutter https://github.com/mobidevke/cookiecutter-flask-api-starter
    
Edit the `config.py` file to adjust database credentials (if needed).

```
cd yourapplication/
pytest tests
```

