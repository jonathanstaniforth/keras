# Keras

A Keras and Jupyter notebook docker image.

Versions of the following have been set to prevent errors and warnings occurring:
- Python 3.6
- Keras 2.2.4
- Tensorflow 1.13.2
- numpy 1.16.1

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
