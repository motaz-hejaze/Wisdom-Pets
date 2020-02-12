Wisdom Pets
======================

* The idea of this project is to investigate built-in features in django
* Models / modelforms / admin portal 
* fundamentals of dealing with templates and static files

Installation
============

1 - Make sure python 3.6 + installed

2 - clone the repo 
  - git clone https://github.com/motaz-hejaze/Wisdom-Pets.git

3 - create a virtualenv environement to install all required packages
  - virualenv venv -p python3.6
  - source venv/bin/activate
  
4 - cd into cloned folder and install required packages for requirements.txt
  - cd Wisdom-Pets
  - pip install -r requirements.txt
  
5 - Make Migrations , Migrate , create super user then run server
  - python manage.py makemigrations
  - python manage.py migrate
  - python manage.py createsuperuser
  - python manage.py runserver
