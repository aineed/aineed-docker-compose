# aineed-docker-compose

## How to run docker compose.
#### Remember to pull last images:
`docker-compose pull`
#### How to run all services:
`docker-compose up -d`
#### How to shutdown all services:
`docker-compose down`
#### Print all running services:
`docker ps`
#### How to see the logs:
`docker logs -f <service_name>'

#### Any update problem:
`
docker-compose stop
docker-compose rm -f
docker-compose pull   
docker-compose up -d
`
