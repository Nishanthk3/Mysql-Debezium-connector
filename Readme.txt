Pull the necessary docker containers
docker pull mysql
docker pull zookeeper
docker pull confluentinc/cp-kafka
docker pull debezium/connect
docker pull obsidiandynamics/kafdrop

and then run the command
docker-compose.yaml

to register a debezium connector to mysql, using the below endpoint with POST method and body debezium-connector.json from this file
http://localhost:8083/connectors