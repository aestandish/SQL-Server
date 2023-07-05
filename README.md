# SQL Server Setup w/ Docker Compose

This code uses docker compose to pull and run a Linux SQL server image. 

### Prerequisites


In order to run this container you'll need docker and docker compose installed.

* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

### Usage

This SQL server was designed to be connected to Azure Data Studio for MacOS. 

To run the container:
```$ docker-compose up -d```

To stop the container:
```$ docker-compose stop```

## Built With

* Docker v24.0.2
* Docker Compose v2.19.1

