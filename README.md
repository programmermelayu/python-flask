# python-flask
Python API with Flask and SQLAlchemy

# Create TODO Task

Simple API to add, update and delete TODO task to demonstrate flask and SQLAlchemy with Python.

## Running the sample

1. Build the server

~~~
pip3 install -r requirements.txt
~~~

2. Run the server from virtual environment

~~~
source env/bin/activate

python app.py
~~~


3. Run from localhost

~~~
python app.py

Browse to http://localhost:1212/
~~~

## Deployment
While you can run from localhost, we also provide Profile, so that it's ready to be deployed into Heroku.

Deploy to Heroku by connecting the repo from Github

~~~
heroku login
heroku create <app-name>

git add .
git commit -m "first commit"
git push
~~~
