# FloShip

#### Description

Django-project with mysql and docker


### Primary installation

#### Build image
````
docker-compose build
````

#### First start
````
docker-compose up db
````

#### Container launch
````
docker-compose up
````
#### DB migrations
````
docker-compose run web python manage.py makemigrations

docker-compose run web python manage.py migrate
````

### django admin for test this app
- http://0.0.0.0:8001/admin