# Project2
2o paradoteo
docker run --name spb_db --rm -e  POSTGRES_PASSWORD=pass123 -e POSTGRES_DB=students --net=host -v pgdata14:/var/lib/postgresql/data  -d postgres:14

docker ps

dockere volume rm pgdata14

22013
22155
22030
