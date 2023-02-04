## Prerequisites

+ Efficient code editor (For eg. Visual studio Code)
+ Install python IDLE.
+ Basic knowledge in html,python,flask,postman,sqlite.

## Project Description

It is a simple todo list project  which is made using RESTFul API in Flask with JWT and Flask-SQLAlchemey for authentication and authorization and testing is done using Postman. 

## Steps in Installation Process

+ Create virtual environment

    virtualenv -p python3 .venv

+ Activate Virtual environment

    venv/Scripts/activate
  
+ Create file called requirements.txt which consists following packages
  
    Flask
    Flask-RESTful
    PyJWT==1.7.1
    Flask-SQLAlchemy

+ Install the packages

    pip install -r requirements.txt
 

## Execute the application 

The application can be executed by runing the server using:

    python api.py

##### note: Here api.db is the application file name.
 

## Database Creation

+ Go to Python Shell

    python
    from api import app, db
    app.app_context().push()
    db.create_all()
    exit()
  
##### note: Here todo.db is the database file name.


## Demo Link

[click here to see the demo]()









