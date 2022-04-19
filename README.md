## Compose sample application

### Python/Flask application using a Redis database

Project structure:

```
.
├── Dockerfile
├── README.md
├── app.py
├── docker-compose.yml
└── requirements.txt
```

[_docker-compose.yml_](docker-compose.yml)

## Docker-compose setup
```
1. Redis image is redislabs/redismod
2. Working folder inside the container is /code
3. Web app depends on Redis so Redis will boot first
Note: You might need to look up the default port for redis.

```

