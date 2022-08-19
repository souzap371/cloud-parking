# cloud-parking

## Run database
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=pablo -e POSTGRES_PASSWORD=abcd1234 -d postgres:10-alpine

## Stop database
docker stop parking-db

## Start database
docker start parking-db
