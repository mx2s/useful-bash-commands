# Useful Docker commands
1. docker exec -it %CONTAINER_ID% /bin/bash  
Connect to docker container (ex. Postrgres) in bash or `/bin/sh` can be used as well if bash isn't supported

2. Run container with custom entrypoint (doesn't exit after its finished executing)
```
docker run --entrypoint "/bin/sh" -it
```

3. Clean up cache etc. (overlay2 directory for example) - all existing containers keep running and all data is still available
```
sudo docker system prune -a -f
```
