# Energydrink microservice environment

The project requires a local running docker environment.

## Postgres
Go to ```/postgres``` and execute the docker compose file to start all necessary postgres databases for the energydrink factory project.

### Start databases

Inside ```/postgres``` execute the following commands

```bash
docker-compose up --no-start
docker-compose start
```
### Stop and remove databases

To stop and remove the running database execute the following commands inside ```/postgres```

```bash
docker-compose stop
docker-compose rm
```
