# MYSQL

## Start a mysql server 

```
docker-compose up -d

# shutdown

docker-compose down -v
```

## Start a mysql server with adminer

```
docker-compose -f docker-compose.yaml -f docker-compose.adminer.yaml up -d

# shutdown
docker-compose -f docker-compose.yaml -f docker-compose.adminer.yaml down -v
```


## Configuration

```
cp env-example .env

# then define your own config
```
