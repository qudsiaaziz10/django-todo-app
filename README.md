# django-todo-app
Please note that this is not a production ready app. It's just a sandbox app I am building to explore different Django features.

### Setup the local environment
Setup a virtual environment and install Django.

```
cd django-todo-app
python3 -m venv django-sandbox-env
source django-sandbox-env/bin/activate
python3 -m pip install Django
python3 -m pip install pytest
python3 -m pip install pytest-django
python3 -m pip install factory-boy
cd user_todo_list

```
### Run database migrations
```
python3 manage.py migrate
```
### Create the super user

```
python3 manage.py createsuperuser
```
### Run the local server

```
python3 manage.py runserver
```