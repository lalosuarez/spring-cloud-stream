# NOTES
To run this project you must have RabbitMQ up and running in your local environmnet.
Use the provided docker-compose.yml to start an instance of RabbitMQ using docker.

- To start RabbitMQ execute: docker-compose up -d
- To stop RabbitMQ execute: docker-compose down

# curl to hit rest service endpoint
curl -d{} http://localhost:8000/greet/World