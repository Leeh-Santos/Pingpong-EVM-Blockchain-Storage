# Pingpong Tournament Score stored at EVM Blockchain - ft_Trancensence Project

SPA Web app with django API's, with local pingpong tournament game, capable of storing and retrieving tournament matches from EVM Blockchains, currently on Sepolia TestNet.

Project Arquitecture: We are using docker-compose to run a little network, with 4 containers

- Nginx Container for certificates since we are using https
- A Django container for REST API
- A Postgres container for Database
- A Vault container for an extra layer of security

For more info Check the docker-compose.yml file

Requirements: You will need Docker and Docker-Compose previously installed in order to run it.

Run it: git clone this repo, cd into it and then use make to trigger the "docker-compose up --build" command of the Makefile

![Description](images-rdme/make.png)

Since the main focus of this repo is to show the EVM integration, lets dive in!

Since the website 




