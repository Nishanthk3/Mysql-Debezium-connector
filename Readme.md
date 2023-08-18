## Docker compose command
```
docker-compose.yaml
```
The above command pulls the below docker containers and starts


```
- mysql
- zipkin
- zookeeper
- confluentinc/cp-kafka
- debezium/connect
- obsidiandynamics/kafdrop
```


To register a debezium connector to mysql, 
Use the below endpoint with POST method and body [debezium-connector.json](https://github.com/Nishanthk3/Mysql-Debezium-connector/blob/main/debezium-connector.json) file
```
http://localhost:8083/connectors
```
