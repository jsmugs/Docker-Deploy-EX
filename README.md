# Docker-Deploy-EX

Commands:

Build an image: docker build --tag fintechexplained-python-docker .

Run Docker image in container: docker run --publish 5000:5000 fintechexplained-python-docker

Run container indefinitely: docker run <image-name> tail -f” command or docker run <image-name> sleep infinity
