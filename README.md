# Docker Container for Strapi

Creates a Docker container for Strapi. Setup to network link in to the docker-postgresql containers.

## Folder

A folders need to be created to store persistant data.

### strapi

This folder contains the Strapi data files

## Create .env to keep all private variables

The follwing is a sample with basic default repsonses in it.

```.env
DATABASE_CLIENT="postgres"
DATABASE_NAME="strapi"
DATABASE_HOST="db"
DATABASE_PORT=5432
DATABASE_USERNAME="strapi"
DATABASE_PASSWORD="strapi"
STRAPI_PORTS="1337:1337"
```
