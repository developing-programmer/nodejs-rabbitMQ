# nodejs-rabbitMQ

## Requirements

1. Create Docker RabbitMQ container:

``sudo docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management``

2. Nodejs

## Getting started

Assuming the docker container is up

1. Open a terminal window and run:

``node subscriber.js``

2. Open another terminal window and run:

``node publisher.js``