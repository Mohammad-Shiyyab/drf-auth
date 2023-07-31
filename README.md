# LAB - Class 33

## Project: Authentication & Production Server

## Author: Mohammad Al-shiyab

## Setup

you need to have docker installed on your machine
```
docker compose up
```
## How to initialize/run your application
```
docker compose run web python manage.py migrate

docker compose run web python manage.py createsuperuser
```

## Tests
python manage.py test