# Docker Playground
Docker playground with some useful docker / compose files

## matomo
This is a simple docker compose for local matomo analytics (https://matomo.org)
server that will run on port 9080. Initially you have to setup the DB connection and user - simply navigate to [http://localhost:9080](http://localhost:9080) and follow the matomo setup. Finally you can test you application tracking/analytics.

Hint: for tracking use the `//localhost:9080/` URL to configure the matomo tracking client.

To run it just type
```
cd matomo
docker compose up
```
