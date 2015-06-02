# playing_with_docker_compose

Task: to create docker-compose.yml file that build 2 project from 2
Dockerfiles stored in the same git repo.

Build:

    docker-compose build

Run:

    docker-compose up -d

View logs:

    docker-compose logs # both pojects
    docker-compose logs a # only project a

Stop & destroy:

    docker-compose stop; docker-compose rm -f
