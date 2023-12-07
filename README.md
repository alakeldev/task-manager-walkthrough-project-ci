# CRUD

FLASK with SQLAlchemy's
Materialize Framework

Note: Don't MIX between using Bootstrap and Materialize in one project it will cause some issue

You can use this framework if you want something common between these two frameworks called: Material Design Bootstrap Framework

###################################################################################################################

__init__.py file:

 The entire application will need to be its own python package so to make this a package, you need a new folder which you will simply call

 taskmanager/. -------> inside of that, a new file called __init__.py this will make sure to initialize our taskmanager application as a package

 allowing us to use our own imports as well as any standard imports

## create an instance of the imported Flask() class

## Create an instance of the imported SQLAlchemy() class

## we did the import here below because the routes file that we are about to create will rely on unsing both 'app' and 'db' variables defined above





#  pip freeze | grep Flask
use this command to know which version you are using for the project Flask and Flask-SQLAlchemy





## if you want create new database coonect to postgres on terminal and write as per below:

psql -U postgres


CREATE DATABASE taskmanager;

\c taskmanager;

\q