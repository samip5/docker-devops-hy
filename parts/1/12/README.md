Commands used for backend:
```
cp ../12/BackendDockerfile .
docker build -f .\BackendDockerfile . -t exercise112-back
docker run -d --name exercise11-back -p 127.0.0.1:8000:8000 exercise112-back
```

Commands used for frontend:
```
cp ../12/FrontDockerfile .
docker build -f ./FrontDockerfile . -t exercise112-front
docker run -d --name exercise11-front -p 127.0.0.1:5000:5000 exercise112-front
```
