# Testing RabbitMQ / Docker / Symfony

##TODO
Make a cluster of nodes after docker-compose, not by:
```
docker exec -it rabbitmq-node-2 rabbitmqctl stop_app                           
docker exec -it rabbitmq-node-2 rabbitmqctl join_cluster rabbit@rabbitmq-node-1
docker exec -it rabbitmq-node-2 rabbitmqctl start_app                          
```
 
