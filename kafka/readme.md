#Запуск kafka + zookeeper + nginx + kafka-ui

docker-compose up -d

docker exec kafka \
kafka-topics --bootstrap-server kafka:9092 \
             --create \
             --topic 3ATECTUM