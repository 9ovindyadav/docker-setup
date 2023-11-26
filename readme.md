
# Docker setup for PHP

Docker setup for PHP development environment to get started developing instantly.

## Get started 
1. Must have **docker** and **docker compose** installed on local machine.
2. Clone the repo in your laptop.
3. move to **docker folder** in terminal in desired development environment.
4. run the following command.
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

7. Start developing PHP application in **src** folder.


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
docker exec -it <container- id / name> bash
```


