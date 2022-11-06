# Set up PostgreSQL

## Install Docker Desktop

[Mac](https://docs.docker.com/desktop/install/mac-install/)

[Windows](https://docs.docker.com/desktop/install/windows-install/)

## Build and run PostgreSQL

```
docker compose up -d
```

## Check the status

```
docker compose ls
```

## Login the DB on the running container

```
docker exec -it mypostgres psql -U postgres -d sho
```

## Logout the container

```
exit
```

## Stop and remove the container

```
docker compose down
```