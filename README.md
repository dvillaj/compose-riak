# Riak Cluster powered by Docker Compose

More information on https://hub.docker.com/r/basho/riak-kv/

## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd compose-riak`

* Run this command `docker-compose up -d coordinator` for the coordinator node
* Run this command `docker-compose scale member=4` to scale the cluster


## Access to postgres: 
* `localhost:5432` to access the data
* `localhost:8098/admin/` to admin the cluster