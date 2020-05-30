The commands:
```
docker volume create --name 11-logs
docker run -d --name exercise11 -p 127.0.0.1:8000:8000 -v 11-logs:/home/node/logs.txt 11-exercise
```
