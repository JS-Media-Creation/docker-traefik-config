# Configuration for traefik as a docker container
## Features
- Certresolver for ssl certificates
- Redirect www to non-www
- Redirect http to https
- Remove X-Powered-By Header
- Enables Traefik Dashboard
## Dependencies
- Docker and docker compose installed on your server
## Get started
- Create a folder "traefik" on your server
- Inside of the "traefik" folder create another folder "data"
- Inside of the "data" folder create an empty acme.json file with chown 600
- Copy the traefik.yaml from this repo into the data folder and make your adjustments
- Copy the docker-compose.yaml from this repo into the "traefik" folder
- Run "docker compose up -d"
- Drink a coffee and have fun ☕
