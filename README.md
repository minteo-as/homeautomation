# zigbee2mqtt, Mosquitto and Node-RED in Docker

## Start
```sh
docker compose up -d
```

## Stop
```sh
docker compose down
```

## Update
```sh
docker compose down
docker compose pull
docker compose up -d
```

## Problems with permissions?
```sh
sudo chown -R 1000:1000 zigbee2mqtt
sudo chown -R 1000:1000 mosquitto
sudo chown -R 1000:1000 node-red
```
