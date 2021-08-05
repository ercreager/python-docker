# python-docker
This repo contains all the files pertaining to Docker's Python-specific getting started guide 

Docker's guide is available at: https://docs.docker.com/language/python/

Note for Windows 10: the Docker guide uses `python3` in the terminal, but `py` works better

`--name` flag in docker commands will set a container name 

example: `docker run -d -p 5000:5000 --name rest-server python-docker`