# Django React Notes App

## Setup

Start with cloning the repository:

```sh
$ git clone https://github.com/ABinfinity/Django-React-NotesApp.git
$ cd Django-React-NotesApp
```

Create a virtual environment (here env) and activate it:

```sh
$ virtualenv env
$ source env/bin/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv`.

Once `pip` has finished downloading the dependencies:
```sh
(env)$ cd mynotes
(env)$ python manage.py runserver
```
Then open your browser and go to --> `http://127.0.0.1:8000/`.

