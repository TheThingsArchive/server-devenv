# The Things Network Server Development Environment

This repository contains the server development environment (devenv) for The Things Network.

The Things Network's back-end contains two services: [croft](https://github.com/TheThingsNetwork/croft), and [jolie](https://github.com/TheThingsNetwork/jolie). They are connected through a RabbitMQ message queue. Jolie stores received data in a MongoDB database that is also used for application state storage.
