# docker-wordpress

A WordPress local development environment using Docker

## Run

```
docker-compose up
```
Open http://localhost:8000 in a web browser

## Shutdown

```
docker-compose down
```
This removes the containers and default network, but preserves your WordPress database

## Cleanup

```
docker-compose down --volumes
```
This removes the containers, default network, and the WordPress database

## Reference

Quickstart Compose and Wordpress - https://docs.docker.com/compose/wordpress/

~~The Official WordPress Docker Image - https://www.sitepoint.com/how-to-use-the-official-docker-wordpress-image/~~

~~Local WordPress Development with Docker: 3 Easy Steps - https://medium.com/@tatemz/local-wordpress-development-with-docker-3-easy-steps-a7c375366b9#.iop6196ec~~
