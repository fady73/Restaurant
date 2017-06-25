# Restaurant

Basic CRUD in python with OAUTH using Google, SQLAlchemy for the ORM (SQLite), and Flask for the Python Framework.

## Files
3.project.py - CRUD operations and logic
3.client_secrets.json - used for OAUTH with Google
3.fb_client_secrets.json - used for OAUTH with Facebook
3.database_setup.py - creates the database tables
3.lotsofcatalogitems.py - populates the database
3.static/styles.css - stylesheet for the application
3.templates/*.html - all the html templates

## Libraries
[SQLAlchemy](http://docs.sqlalchemy.org/en/rel_1_0/intro.html#installation-guide) - ORM used to interact with the DB. 
[Flask](http://flask.pocoo.org/docs/0.10/installation/) - Python microframework used to create REST API
[Twitter Bootstrap](http://getbootstrap.com/) - CSS Framework used for grid and html elements.
[Jquery-2.1.4](https://jquery.com/) - JavaScript library to ease cross browser compliance. 


## Instalation

To run this catalog project you will need python 2.7.9. 
To install python go to [this link](https://www.python.org/downloads/)

Depending on your setup you might need [SQLalchemy](http://docs.sqlalchemy.org/en/rel_1_0/intro.html#installation-guide) and [Flask](http://flask.pocoo.org/docs/0.10/installation/). Follow their links and installation guidelines accordingly.

## Running the application

Open your terminal & cd to this repo. Then type in the following commands:

1. ``` python database_setup.py ``` to create the database

2. ``` python lotsofcatalogitems.py ``` to populate the database

3. ``` python project.py ``` to launch the app. Navigate to localhost:5000 in your browser.




