#
# RabbitMQ Dockerfile
#
# https://github.com/dockerfile/rabbitmq
#

# Pull base image.
FROM rabbitmq:latest

# Install RabbitMQ.
RUN \
  apt-get update && \
  rabbitmq-plugins enable rabbitmq_management && \
  rabbitmq-plugins enable rabbitmq_shovel rabbitmq_shovel_management


# Expose ports.
EXPOSE 5672
EXPOSE 15672
EXPOSE 25676