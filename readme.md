# Hello Wolrd
This sample is a simple Python program to display "Hello, World!" in Docker environment.

## Run
```
docker run -it --rm -v $PWD/src:/data -w /data python:3 python main.py
```