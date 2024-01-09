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
sudo chown -R zigbee2mqtt
sudo chown -R mosquitto
sudo chown -R node-red
```
