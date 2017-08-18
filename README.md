# jupyter-docker

Jupyter notebook on Docker serverd up by Django

![](https://img.shields.io/badge/built%20with-Cookiecutter%20Django-ff69b4.svg)


## Installation
1. Install [docker](https://docs.docker.com/engine/installation/)
2. Clone this project
```
git clone https://github.com/lukeaus/jupyter-notebook-django-docker.git
```

## Running
Note: First time takes a while to install everything
```
./start.sh
```
Then follow the instructions onscreen and copy the url and paste it in your browser once
it appears.


## Exiting
To exit, simply press ```control + c``` then press ```y``` then hit enter.


## Saving Notebooks
Put your notebooks in the ```notebooks``` directory


## Unimportant Fluff

####  Setting Up Your Users
* To create a **normal user account**, just go to Sign Up and fill out the form. Once you submit it, you'll see a "Verify Your E-mail Address" page. Go to your console to see a simulated email verification message. Copy the link into your browser. Now the user's email should be verified and ready to go.

* To create an **superuser account**, use this command:

    $ python manage.py createsuperuser

For convenience, you can keep your normal user logged in on Chrome and your superuser logged in on Firefox (or similar), so that you can see how the site behaves for both kinds of users.

#### Test coverage
To run the tests, check your test coverage, and generate an HTML coverage report:

    $ coverage run manage.py test
    $ coverage html
    $ open htmlcov/index.html

#### Running tests with py.test

  $ py.test

#### Live reloading and Sass CSS compilation

[Live reloading and SASS compilation](http://cookiecutter-django.readthedocs.io/en/latest/live-reloading-and-sass-compilation.html)

