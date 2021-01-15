# db
Start app in docker for quck testing


## Start containers

## Container types
- redis
- postgres
- nginx

## Commands
```shell
# start one
docker-compose up -d ${CONTAINER_TYPE}

# stop one
docker-compose stop ${CONTAINER_TYPE}

# start all
docker-compose up -d

# stop all
docker-compose stop

# remove all
docker-compose down

# list
docker-compose ps
```