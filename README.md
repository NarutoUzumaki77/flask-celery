# Asynchronous Tasks with Flask and Celery

Example of how to handle background processes with Flask, Celery, and Docker By Michael Herman. https://testdriven.io/blog/flask-and-celery/ 

### Quick Start

Spin up the containers:

```sh
$ docker-compose up -d --build --scale worker=3
```

Open your browser to [http://localhost:5004](http://localhost:5004).

To monitor task queue with [Flower](https://flower.readthedocs.io/en/latest/index.html), Open browser to http://localhost:5556
