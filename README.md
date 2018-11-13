# TODO LIST. Following a tutorial.

https://www.youtube.com/watch?v=sVF5mzhlV-4&list=PLw02n0FEB3E0smsGO7EcnSqR-PCAWruJC

## NOTES
Additional commands/notes required to complete each step/video.

### 1-2-3. Setup
```export PYTHONPATH=$PYTHONPATH:/vagrant/www
export DJANGO_SETTINGS_MODULE=todo.settings

mysql-client-core-5.7
mysql-server

apt-get install libmysqlclient-dev
pip install mysqlclient
```

### 3. MySQL Database
Manually create our database before performing the migrations with django.
```mysql -u root -p
CREATE DATABASE todo;
django-admin migrate
```

### 9. API Endpoint - Django rest
Specify project name this time since we are not using the conventional django app structure. We are just creating the models, views etc in the main project folder.
```django-admin makemigrations todo
```

## TODO
Use the router in the urls.py.
