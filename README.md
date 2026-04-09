# Kafka-Connect---Building-Data-Pipelines-With-Kafka

docker run --name mysql-kafka -e MYSQL_ROOT_PASSWORD=root -p 3306:3306 -d mysql:latest

docker exec -it mysql-kafka mysql -u root -p

docker rm -f mysql-kafka
