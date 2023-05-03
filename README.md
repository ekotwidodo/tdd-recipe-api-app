# TDD-recipe-api-app
 Recipe API project using REST API with Python, Django REST Framework, and Docker using Test Driven Development (TDD)


## Resume

1. Create a Github Repository called `tdd-recipe-api-app` and custom the repo, such as public/private repo, README, gitignore, and license
2. Create a DockerHub Access Token
3. Set the `DOCKERHUB_USER` and `DOCKERHUB_TOKEN` through `Settings > Secrets and variables > Actions > New repository secret`
4. Clone the repo to local machine and add some files, such as `requirements, docker, flake8`
5. To build a docker image from docker file, use command `docker build .`
6. To build a docker image from docker compose, use the command `docker-compose build .`
7. Run the docker compose using command `docker-compose run --rm app sh -c "django-admin startproject app ."`
8. Run the project using command `docker-compose up`
9. For linting issue, use command `docker-compose run --rm app sh -c "flake8"` and for tests issue use command `docker-compose run --rm app sh -c "python manage.py test"`
10. To stop the project, press Ctrl + C