
# Docker setup for PHP

Docker setup for PHP development environment to get started developing instantly.

## Get started 
1. Must have **docker** and **docker compose** installed on local machine.
2. Clone the repo in your laptop.
```
git clone https://github.com/9ovindyadav/php-docker-setup.git
```
3. Move to the cloned repo.
```
cd php-docker-setup
```
4. Run the following command.
```
docker compose up -d --build
```
5. In browser for web page
```
http://localhost:8000
```
6. In browser for phpmyadmin
```
http://localhost:8080
```
- server - localhost
- user - root
- passowrd - root

7. Start developing PHP application.


## Docker commands 
1. To check available images
```
docker images
```
2. Currently running images
```
docker ps
```
3. Stop all the container
```
docker compose down
```
4. SSH in container
```
docker exec -it <container- id or name> /bin/bash
```


