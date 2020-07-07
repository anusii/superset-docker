## Superset

Port: 8088

Access: localhost:8088

```bash
# inside superset_docker/
docker build --rm -t superset_docker:latest .
docker run --rm -d -p 8088:8088 --env-file ../.env --name superset superset_docker:latest
```
