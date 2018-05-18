start containers in daemon mode
```bash
docker-compose up -d
```

start in daemon mode and also force recreate one of them
```
docker-compose up -d --force-recreate <container_1>
```

view logs for 1 - n containers
```bash
docker-compose logs -f --tail=100 <container_1> <container_2>
```

enter a container with bash
```bash
docker-compose exec <container_name> /bin/bash
```

