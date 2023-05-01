# IPv64 Client on Docker

![alt text](https://ipv64.net/img/ipv64_logo.svg "Logo")

## Hardware Requirements

 - Docker
 
## Installation

Instructions for Compose V2 (From the end of June 2023 Compose V1 won’t be supported anymore) https://docs.docker.com/compose/


1. Clone repo
```sh
git clone https://github.com/ipv64net/ipv64_client.git
cd ipv64_client/devices/Docker/
```
2. Build
```sh
docker compose build
```
3. Edit the Node #Secret in the docker-compose.yml
4. run
```sh
docker compose up -d
```