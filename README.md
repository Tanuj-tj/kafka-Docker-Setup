# kafka-Docker-Setup

- Clone this repository

- Move inside the cloned directory and execute the following command (make sure the docker in running)

```
docker compose up -d
```


- Now once the container is up, use the following command to enter the kafka shell running inside the container

```
docker exec -it -w /opt/kafka/bin broker sh
```
