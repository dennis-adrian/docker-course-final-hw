# Instructions

## Important
Execute the `script.sh` file to set the configurations for the sonarqube container.
```sh
sudo sh script.sh
```
## Start Containers
Use docker-compose.yml to start all the containers.
```sh
docker-compose up -d
```
If the image for nodeapp is not build, it'll build it. Otherwise, it'll just start the container