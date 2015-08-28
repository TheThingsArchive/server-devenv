# The Things Network Server Development Environment

This repository contains the server development environment (devenv) for The Things Network.

The Things Network's back-end contains two services: [*croft*](https://github.com/TheThingsNetwork/croft), and [*jolie*](https://github.com/TheThingsNetwork/jolie). They are connected through a RabbitMQ message queue. Jolie stores received data in an InfluxDB database and will MongoDB for application state storage.

Note that [*dike*](https://github.com/TheThingsNetwork/dike) is for basic demonstration purposes only and will be replaced shortly by an example that uses proper message routing.
