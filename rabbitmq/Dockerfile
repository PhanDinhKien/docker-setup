# Use the official RabbitMQ image with management plugin
FROM rabbitmq:3.12-management

# Set default credentials
ENV RABBITMQ_DEFAULT_USER=admin
ENV RABBITMQ_DEFAULT_PASS=admin

# Expose RabbitMQ ports
EXPOSE 5672 15672

# Start RabbitMQ server
CMD ["rabbitmq-server"]