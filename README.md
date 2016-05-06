# Postgresql-Docker-Rails

**Get it running:**

``$ docker-compose up ``

**Run Migrations:**

``$ docker-compose run --rm web rake db:migrate ``

**Testing the running PostgreSQL**

To test the running container we can use any client

  Open shell container db  from docker-compose.yml

  ``docker exec -it <id-container-db> /bin/bash``
  
  Connect PostgreSQL command line 

``psql -h localhost -p 5432 -U pguser -W pgdb``

  When you are prompted for password, type: pguser

Enjoy !!!
