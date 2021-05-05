#docker_communications

I am trying to make connection between 2 containers of docker and communicate messages using message brocker such as Rabbitmq .
[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest
## Installation

```bash
$ docker pull rabbitmq:3-management
```

## Running

```bash
$ docker run --rm -it --hostname my-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management
```
 the port 5672 is used for the RabbitMQ client connections, and the port 15672 is for the RabbitMQ management website
 
 ## Open in browser

```bash
 http://localhost:15672 
```
 We now have an instance of RabbitMQ server.
