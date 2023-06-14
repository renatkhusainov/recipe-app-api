# recipe-app-api
Recipe API Project

docker-compose build

docker-compose up

docker-compose stop

docker-compose run --rm app sh -c "python manage.py test"

docker-compose run --rm app sh -c "flake8"

docker-compose run --rm app sh -c "python manage.py startapp user"
