# docker-python3
Python 3.7 Container with Common Packages

## docker run
```
docker run --name docker-python3 -d --restart=always -v $PWD:/app:z -t amarinboonkirt/docker-python3
```
## ssh to container
```
docker exec -it docker-python3 bash
```
## start django
```
docker exec -it docker-python3 bash -c "cd /app; python manage.py runserver 0.0.0.0:8000"
```
