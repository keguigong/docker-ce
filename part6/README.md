### Recap and cheat sheet

```sh
docker-machine env myvm1
eval $(docker-machine env myvm1)
docker stack deploy -c docker-compose.yml getstartedlab
docker stack ps getstartedlab
docker-machine ssh myvm1 "mkdir ./data"
docker stack deploy -c docker-compose.yml getstartedlab
docker service ls
```