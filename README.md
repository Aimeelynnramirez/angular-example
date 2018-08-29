# angular-example
Example for template generating 


Docker examples for learning: 
https://www.drupal.org/docs/develop/local-server-setup/docker-development-environments

stop all containers:
docker kill $(docker ps -q)

remove all containers
docker rm $(docker ps -a -q)

remove all docker images
docker rmi $(docker images -q)
