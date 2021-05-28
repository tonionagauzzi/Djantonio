# Djantonio
Samples for [CS50](https://cs50.jp/) Web 2020
* [myapp](./myapp) : Sample app for [Django](https://cs50.jp/web/2020/django/notes/) > [Django](https://cs50.jp/web/2020/django/notes/#django)
* [newyear](./newyear) : Sample app for [Django](https://cs50.jp/web/2020/django/notes/) > [Template](https://cs50.jp/web/2020/django/notes/#template) -> [Conditionals](https://cs50.jp/web/2020/django/notes/#conditionals)
* [tasks](./tasks) : Sample app for [Django](https://cs50.jp/web/2020/django/notes/) > [Tasks](https://cs50.jp/web/2020/django/notes/#tasks)
* [users](./users) : Sample app for [SQL, Models, and Migrations](https://cs50.jp/web/2020/sql-models-and-migrations/notes/) > [Users](https://cs50.jp/web/2020/sql-models-and-migrations/notes/#users)

## Learning environment
* macOS Catalina 10.15.7
* Python 3.9.5

## How to setup
After [download Python](https://www.python.org/downloads/),
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
pip3 install Django
```

## How to start server
```
cd Djantonio
python3 manage.py migrate
python3 manage.py runserver
```

## How to create admin user
```
python3 manage.py createsuperuser
```
http://localhost/admin
