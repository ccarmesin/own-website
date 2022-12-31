# My own website

## Setup

1. Build the docker container

`docker build . -t own-website`

2. Run docker container:

`docker run -it --rm -d -p 8080:80 own-website`