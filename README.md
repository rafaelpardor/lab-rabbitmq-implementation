# Rabbitmq Laboratory

## Why you would use a Message Queue System

## RabbitMQ Tutorial

```bash
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management
```

Run the follow commands, after running the docker rabbitmq image.

```bash
go run receiver.go
go run send.go
```

