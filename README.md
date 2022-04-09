# demo-flask-app-builder
Simple and rapid application development framework, built on top of Flask. It includes detailed security, auto CRUD generation for your models and google charts.

### Installation 
pip install Flask-AppBuilder

### To download app skeleton from Github (Will ask for App name and DB type(SQLAlchemy))
flask fab create-app

## Following steps need to be run from the app folder
### To create admin user 
flask fab create-admin

### To Run the app using 
set FLASK_APP=app
set FLASK_DEBUG=1
flask run

### URL 
http://127.0.0.1:5000/
