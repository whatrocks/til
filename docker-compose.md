start containers in daemon mode
```bash
docker-compose up -d
```

view logs for 1 - n containers
```bash
docker-compose logs -f --tail=100 <container_1> <container_2>
```

enter a container with bash
```bash
docker-compose exec <container_name> /bin/bash
```

