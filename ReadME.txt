Integration of Drupal web management framwork and PostgreSQL a database management system to store the contents of Drupal web framework with docker in the form of docker-compose file

Drupal is a free and open-source web content management framework written in PHP
PostgreSQL also known as Postgres, is a free and open-source relational database management system emphasizing extensibility and SQL compliance.

to start the drupal framework you need the docker-compose.yml file
and terminal to the directory where docker-compose.yl file is 
run the command  docker-compose up
(the process needed internet in order to download the image of PostgresSQL and Drupal OS from Docker Hub)
after the cmd sucessfully run
goto http://localhost:8080
and fill the required details according to the screenshots provided in this repo

these are the credentials (you can change these by editing in docker-compose.yml file)

dbname=drupaldb
user=drupal
pass=drupalpass
hostname=postgresdb

see screenshots for each detailed steps

at last configure your site by filling out information of your site

   Voila you are good to go...
ALL SET

