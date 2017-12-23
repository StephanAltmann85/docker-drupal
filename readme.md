
## Information
add following to /etc/hosts
    172.12.1.1      salty.dev
    
database-host: db

## How to start
    docker-compose up -d
(docker-compose 1.8.x is required)

## At first start
    chmod -R 777 repositories/
    


## Export database dump
    docker exec -it [name of db-container] /usr/local/bin/export/dump.sh

## access container's bash
    docker exec -it [name of container] bash
    
## XDebug
idekey=phpstorm
