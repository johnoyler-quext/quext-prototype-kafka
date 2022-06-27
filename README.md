## Some useful commands

### Start Kafka and related/requred processes locally
docker-compose up -d 

### Stop Kafka 
docker-compose stop 

### Publish a message to a topic
docker exec -it qxt-kafka kafka-console-producer.sh --broker-list localhost:9092 --topic topic-name

## Some useful tools

* [Offset Explorer](https://offsetexplorer.com/download.html)