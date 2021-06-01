# wordpress-local

Run wordpress locally in a docker container for development.

#### Start Wordpress

`docker-compose up`

#### Set Up Wordpress

Navigate to `127.0.0.3:80` or your configured port and set up the wordpress site. Congrats you now have a wordpress dev backend!

#### Tear Down Containers (keep database)

`docker-compose down`

#### Remove containers and database

`docker-compose down --volumes`
