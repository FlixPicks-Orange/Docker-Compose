# Docker-Compose YML

This repository contains the docker-compose.yml file used to build the FlixPicks Prototype.

## How to Use

1. Clone all repositories (incluidng this one) in the same parent directory
2. Copy the 'docker-compose.yml' file to this parent directory
3. Build the images and launch containers using the docker-compose commands below


## Docker-Compose Commands
NOTE: These commands should be run from the parent directory containing all the repositories.

### Build Images
> docker-compose build

### Start Services (Containers and Network)
> docker-compose up
Note: Add -d to run detached (i.e. background)

### Shutdown Services
> docker-compose down
NOTE: Use the clean-up method below, otherwise you will need to manually clean-up containers.

### Remove and Clean-up Containers/Images
> docker-compose down --rmi all -v --remove-orphans