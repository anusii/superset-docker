## Superset

Port: 9999
Access: localhost:9999

```bash
# inside superset_docker/
docker build --rm -f Dockerfile -t superset_image:latest .
docker run --rm -d -p 9999:8088 --env-file ../.env --name superset superset_image:latest
```
