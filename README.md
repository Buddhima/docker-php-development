# docker-php-development
This repository is the foundation for Docker based PHP development projects

.env file consists of versions of each products

Docker Bind-Mounts are used for apache, php and mysql docker containers

mysql docker opens port 3306 via port 4306 in host machine

Apache server is using port 80 of the hot machine

apache and php are separated in to 2 images, to encourage "single process per container"

Your PHP application should go to "public_html" folder.

Having docker and docker-compose is a prerequisite.

To start the deployment use :  docker-compose up -d
To stop the deployment use :  docker-compose down

This deployment is based on : 	https://github.com/mzazon/php-apache-mysql-containerized/ 



