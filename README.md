# Keras

A Keras and Jupyter notebook docker image.

The following package versions have been set:
- Python 3.6
- Keras 2.2.4
- Tensorflow 1.13.2
- Numpy 1.16.1
- Pillow 6.1.0

## Quick start

Run the docker image:
```
docker run -p 8888:8888 jonathanstaniforth/keras:cpu
```

> Make sure to get the generated token for Jupyter notebook from the CLI and
> navigate to localhost:8888.

Run with a mount folder:
```
docker run -p 8888:8888 -v "$(pwd)"/data:/tf jonathanstaniforth/keras:cpu
```

> Set the container path to /tf to access the folder with Jupyter notebook.
