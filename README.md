# SIDERMIT installer

Docker-compose file to run an instance of sidermit app

## Process

1. Install docker-cli from [get-docker site](https://docs.docker.com/get-docker/)
1. Download this project from [here](https://github.com/SIDERMIT/installer/archive/v1.0.0.zip)
1. Uncompress zip file downloaded from previous step
1. Open terminal and go to project folder
1. Execute command `docker-compose -f docker-compose.yml up`
1. go to [http://localhost:8000/](http://localhost:8000/)


## Update version

If a new version of project was released you should follow next steps:

1. Stop running current docker-compose command with `ctrl + c` (if it's running)
1. Execute command `docker-compose pull` and wait
1. Start program again `docker-compose -f docker-compose.yml up`

# Faqs

## Hardware assisted virtualization and data execution protection must be enable in the BIOS

If you see this message on computer where docker is installing you need to follow instructions in this video: [click here](https://www.youtube.com/watch?v=MOuTxfzCvMY&ab_channel=Triple-ATechSolutions)
