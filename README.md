This is a Django Learning Test.

https://programmer.group/django-3-tutorial-and-crud-example-with-mysql-and-bootstrap.html

# Create and activate conda environment
conda create -n env
conda activate env

# Install Django and python3.6
conda install django
conda install python=3.6

# Create project
django-admin startproject firstSite

# Launch Site locally
cd to folder
python manage.py migrate
python manage.py runserver
Then open web browser and enter the http://127.0.0.1:8000/ to see django page.

# Projects vs. apps
What’s the difference between a project and an app? An app is a Web application that does something – e.g., a Weblog system, a database of public records or a small poll app. A project is a collection of configuration and apps for a particular website. A project can contain multiple apps. An app can be in multiple projects.

# create polls app
python manage.py startapp polls
