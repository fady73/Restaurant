# Restaurant

Basic CRUD in python with OAUTH using Google, SQLAlchemy for the ORM (SQLite), and Flask for the Python Framework.

## Files
1 project.py - CRUD operations and logic <br>
2 client_secrets.json - used for OAUTH with Google <br>
3 fb_client_secrets.json - used for OAUTH with Facebook <br>
4 database_setup.py - creates the database tables <br>
5 lotofmenus.py - populates the database <br>
6 static/styles.css - stylesheet for the application <br>
7 templates/*.html - all the html templates

## Libraries
[SQLAlchemy](http://docs.sqlalchemy.org/en/rel_1_0/intro.html#installation-guide) - ORM used to interact with the DB. <br>
[Flask](http://flask.pocoo.org/docs/0.10/installation/) - Python microframework used to create REST API. <br>
[Twitter Bootstrap](http://getbootstrap.com/) - CSS Framework used for grid and html elements. <br>
[Jquery-2.1.4](https://jquery.com/) - JavaScript library to ease cross browser compliance. <br>


## Instalation

To run this catalog project you will need python 2.7.9.  <br>
To install python go to [this link](https://www.python.org/downloads/). <br>

Depending on your setup you might need [SQLalchemy](http://docs.sqlalchemy.org/en/rel_1_0/intro.html#installation-guide) and [Flask](http://flask.pocoo.org/docs/0.10/installation/). Follow their links and installation guidelines accordingly.<br>

## Running the application

Open your terminal & cd to this repo. Then type in the following commands:

1. ``` python database_setup.py ``` to create the database

2. ``` python lotsofmenus.py ``` to populate the database

3. ``` python project.py ``` to launch the app. Navigate to localhost:5000 in your browser.




