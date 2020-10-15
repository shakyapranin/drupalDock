# Docker container to run a Drupal 7 Application

# For local development 

## $ docker-compose up -d

# For determining the docker processes running

## $ docker ps

# After determing the ports on which services are served, Run the following command

## $ docker exec -it drupal /bin/bash
## $ drush dl
## $ tar -C . -xvf drupal-7.x/drupal-7.x.tar.gz --strip-components=1


# In terms of the database you can use the phpmyadmin interface to create a database as per requirement.