# zigbee2mqtt, Mosquitto and Node-RED in Docker

Remember to update hostnames in `nginx.conf`

## Usage
### Start
```sh
docker compose up -d
```

### Stop
```sh
docker compose down
```

### Update
```sh
docker compose down
docker compose pull
docker compose up -d
```

## Problems
### Wrong permissions (this fixes almost all problems)
```sh
docker compose down
sudo chown -R 1000:1000 zigbee2mqtt
sudo chown -R 1000:1000 mosquitto
sudo chown -R 1000:1000 node-red
docker compose up -d
```
