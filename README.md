// create and start containers
docker-compose up

// start services with detached mode
docker-compose -d up

// start specific service
docker-compose up <service-name>

// list images
docker-compose images

// list containers
docker-compose ps

// start service
docker-compose start

// stop services
docker-compose stop

// display running containers
docker-compose top

// kill services
docker-compose kill

// remove stopped containers
docker-compose rm

// stop all contaners and remove images, volumes
docker-compose down

// check logs in conteiner
docker logs #id container

// list of images
docker images

// list of containers
docker ps

docker system prune (-af)

// connect to container with bash
docker exec -it id bash

// run mongo
mongo -u news-app -p secret
