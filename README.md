# Postgresql-Docker-Rails

Docker image for PostgreSQL

**Get it running:**

``$ docker-compose up ``

**Run Migrations:**

``$ docker-compose run --rm web rake db:migrate ``

**Testing the running PostgreSQL**

To test the running container we can use any client, even the commandline one:


``psql -h localhost -p 5432 -U pguser -W pgdb``

When you are prompted for password, type: pguser

Enjoy !!!
