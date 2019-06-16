# Spoken-Tutorial
A web app created using django framework
# Requirements
Python 3.6 Django==2.0.3

# How to run it?
Install virtualenv : 
$ sudo apt install python-virtualenv <br/>
Create a virtual environment : 
$ virtualenv env -p python3 <br/>
Activate the env : 
$ source env/bin/activate <br/>
Change directory to spokentut : 
$ cd spokentut <br/>
Make migrations : 
$ python manage.py makemigrations <br/>
Migrate the changes to the database : 
$ python manage.py migrate <br/>
Run the server : 
$ python manage.py runserver  <br/>
