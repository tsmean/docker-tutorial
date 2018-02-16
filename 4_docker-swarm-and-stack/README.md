## Docker Swarm & Stack Tutorial

Video Tutorial: https://youtu.be/m6WgX_LBtEk

To run this locally, run:

```
docker swarm init
docker build -t hello -f hello-service/Dockerfile hello-service
docker build -t goodbye -f goodbye-service/Dockerfile goodbye-service
docker stack deploy -c ./docker-compose.yml talk
```

To tear down the stack:
```
docker stack rm talk
```
