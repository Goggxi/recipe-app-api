# recipe-app-api

Script notes:

```bash
# Context - test, app, etc.
docker-compose run --rm app sh -c "<context>"

# Build the docker image
docker-compose build

# Check linting
docker-compose run --rm app sh -c "flake8"

# Create a new Django project
docker-compose run --rm app sh -c "django-admin startproject app ."

# Run Tests
docker-compose run --rm app sh -c "python manage.py test"

# Run the Django app
docker-compose up
```
