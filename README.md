# REST framework tutorial

Source code for the [Django REST framework tutorial][tut].

[tut]: http://www.django-rest-framework.org/tutorial/1-serialization

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


# Updates

To make it work in Mac OS Sonoma 14.5 with Python 3.10.13, I had to run these commands to install requirements:

- brew install postgresql
- echo "cython<3" > /tmp/constraint.txt
- PIP_CONSTRAINT=/tmp/constraint.txt pip install -r requirements.txt
