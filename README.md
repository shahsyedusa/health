# HealthQuiz

## What is it?

Health Quiz application using:
- Python 3
- SQLAlchemy
- FastAPI

Autogenerates OAS spec for utilizing on the front-end

## Instructions

Resources: https://medium.com/@marvinjungre/get-postgresql-and-pgadmin-4-up-and-running-with-docker-4a8d81048aea

`docker run --name pgadmin-container -p 5050:80 -e PGADMIN_DEFAULT_EMAIL=user@email.com -e PGADMIN_DEFAULT_PASSWORD=mysecretpassword -d dpage/pgadmin4`

`docker run --name healthdb -e POSTGRES_PASSWORD=mysecretpassword -p 5432:5432 -d postgres`

`docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' sqltutorial`