# Useful Docker commands
1. docker exec -it %CONTAINER_ID% bash

Connect to docker container (ex. Postrgres) in bash

2. Docker run container with custom entrypoint (doesn't exit after its finished executing)
```
docker run --entrypoint "/bin/sh" -it
```
