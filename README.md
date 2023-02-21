# Docker Playground
Docker playground with some useful docker / compose files

## matomo
This is a simple docker compose for local matomo analytics (https://matomo.org)
server that will run on port 9080. You can test you application tracking/analytics.

Hint: in the tracking code use `//localhost:9080/` as matomo/tracking-URL.

To run it just type
```
cd matomo
docker compose up
```