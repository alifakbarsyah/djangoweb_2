# djangoweb_2
[![Python Version](https://img.shields.io/badge/python-3.6-brightgreen.svg)](https://python.org)

Django web with github and oxford API,

This project is just an example on how to consume RESTful APIs using Django.

## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/alifakbarsyah/djangoweb_2.git
```

Install the requirements:

```bash
pip install -r requirements.txt
```

*PS: If you have issues installing either `gunicorn` or `psycopg2`, you can remove them from the requirements.txt file and run the command again.*

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.

*PS: Set your API key in settings.py*

Inspired from [How to Use RESTful APIs with Django](https://simpleisbetterthancomplex.com/tutorial/2018/02/03/how-to-use-restful-apis-with-django.html).
