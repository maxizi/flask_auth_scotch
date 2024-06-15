# How to properly implement register and login mechanism with flask
## How to execute and run
1. Install packages: 
    - pip install flask flask-sqlalchemy flask-login
1. Run on git bash
    - export FLASK_APP=project
    - export FLASK_DEBUG=1
1. Build user database: Run in python shell
    - from project import db, create_app, models
    - app = create_app()
    - with app.app_context():
        db.create_all()

1. flask run

## Links
Link to repo: https://github.com/maxizi/flask_auth_scotch