#  RabbitMQ Docker Setup

Easily run **RabbitMQ 4.1.0-rc.1** with the **Management Plugin** using Docker.

---

## Docker Image

Pull the RabbitMQ image with the management UI:

```bash
docker pull rabbitmq:4.1.0-rc.1-management 


## Use the following command to start RabbitMQ in a Docker container:

docker run --rm -it -p 15672:15672 -p 5672:5672 rabbitmq:4.1.0-rc.1-management
