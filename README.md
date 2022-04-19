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

## Dockerfile task notes:
```
1. Working folder inside the container is /code
2. In Python applications, the file listing all dependencies is called requiements.txt. Treat this in the same way you would treat a package.json file
3. You may need to look up the command to install dependencies in Python.
3. You may need to look up the command to start up a Python web app once everything else is ready.

Note: You might need to look up the default port for redis.
```

## Docker-compose task notes:
```
1. Redis image is redislabs/redismod
2. Working folder inside the container is /code
3. Web app depends on Redis so Redis will boot first

Note: You might need to look up the default port for redis.


```

