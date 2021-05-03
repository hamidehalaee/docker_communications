# docker_example
I am trying to make connection between 2 containers of docker and communicate messages using message brocker such as Rabbimq docker image.

## Installation

```bash
$ docker pull rabbitmq:3-management
```

## Running

```bash
$ docker run --rm -it --hostname my-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management
```

