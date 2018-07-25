# TO-DO-List-Django

Simple ToDo List created with Django to practice this framework.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
1. Create your virtual environment
2. Clone this repository
3. Install requirements
4. Initialize database
5. Run TODO app
```

### Installing and deployment

A step by step series of examples that tell you how to get a development env running

1. Create new virtual environment, for example with virtualenvwrapper:

```
$ pip install virtualenvwrapper
$ mkvirtualenv example_venv
```

2. Clone this repository:

```
$ git clone https://github.com/3Cement/TO-DO-List-Django/
```
2.1. Change you time zone in settings.py if you are in different one than Europe/London

```
TIME_ZONE = 'Europe/London'
```

3. Install requirements:

```
$ pip install -r requirements.txt
```

4. Initialize database

```
$ python3 manage.py makemigrations
$ python3 manage.py migrate
```

5. Run TODO app (in folder with manage.py file):

```
$ python manage.py runserver
```
## Screenshots

## Running the tests

Run tests from folder with manage.py file:

```
$ python manage.py test
```

## Built With

* [Django](https://www.djangoproject.com/) - The web framework used
* [SQLite](https://www.sqlite.org/index.html) - SQL database engine

## Contributing

Please feel free to contribute this project and contact me for questions.

## Authors

* **Daniel Milewski** - https://github.com/3Cement

See also the list of [contributors](https://github.com/3Cement/TO-DO-List-Django/graphs/contributors) who participated in this project.

## License

This project is licensed under the Apache License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Big thanks to Mozilla Developers for creating this amazing tutorial (https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django) which helps me to learn Django
