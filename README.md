# Microservice Setup with Docker Swarm

This repo contains the docker-compose and the docker-stack file for a simple microservice architecture. It has an API that serves country information and a very simple react client that queries the api. On top of that it has a nginx container that is configured as a reverse proxy. The repos of all the individual services can be found here:

*   API: https://github.com/Piepongwong/countriesApi
*   Client: https://github.com/Piepongwong/country-client
*   NGINX Reverse Proxy: https://github.com/Piepongwong/reverse-proxy