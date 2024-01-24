# RabbitMQ with Dotnet

before run the Send and Receive projects we need run docker image for rabbitmq

docker run -itd --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.12-management

