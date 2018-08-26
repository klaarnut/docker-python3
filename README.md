# docker-python3
Python 3.7 Container with Common Packages

## docker run
```
docker run --name docker-python3 -d --restart=always -v $PWD:/app:z -t amarinboonkirt/django-python3
```
## ssh to container
```
docker exec -it docker-python3" bash
