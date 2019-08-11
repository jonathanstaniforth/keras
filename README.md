# Keras

A Keras and Jupyter notebook docker image, using numpy version 1.16.1 to prevent issues.

## Quick start

Run the docker image, forwarding to port 8888 on localhost:
```
docker run -d -p 8888:8888 jonathanstaniforth/keras
```

Add a volume to the docker container:
```
docker run -d -p 8888:8888 --mount source=data,target=/notebook jonathanstaniforth/keras
```

To interact with the docker container:
```
docker exec -it <container-id> bash
```
