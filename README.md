# Docker image for Pipe Network
> Krishna Kumar

[![Quay image](https://img.shields.io/badge/quay--image-cbcities--pipe-network-ff69b4.svg)](https://quay.io/repository/cbcities/pipe-network)
[![Docker hub](https://img.shields.io/badge/docker--hub-cbcities--pipe-network-ff69b4.svg)](https://hub.docker.com/r/cbcities/pipe-network)
[![CircleCI](https://circleci.com/gh/cb-cities/pipe-network-container.svg?style=svg)](https://circleci.com/gh/cb-cities/pipe-network-container)
[![](https://images.microbadger.com/badges/image/cbcities/pipe-network.svg)](http://microbadger.com/images/cbcities/pipe-network)

## Tools
* Clang 4.0
* CMake 3
* Eigen 3.
* GCC 7
* Vim

# Using the docker image
* The docker image can be used directly from the Docker Hub or Quay.io
* Pull the docker image `docker pull cbcities/pipe-network` or `docker pull quay.io/cbcities/pipe-network`
* To launch the `cbcities/pipe-network`  docker container, run `docker run -ti cbcities/pipe-network:latest /bin/bash` or `docker run -ti quay.io/cbcities/pipe-network:latest /bin/bash`

# To login as root
* Launching docker as root user: `docker exec -u 0 -ti <containerid> /bin/bash`

# Creating an image from the docker file
* To build an image from docker file run as root `docker build -t "cbcities/pipe-network" /path/to/Dockerfile`
* `docker history` will show you the effect of each command has on the overall size of the file.
