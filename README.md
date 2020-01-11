#docker-example

https://runnable.com/docker/python/dockerize-your-python-application

docker build -t python-barcode .

docker run python-barcode

if an error pops up:
    sudo groupadd docker
    sudo usermod -aG docker $USER
    newgrp docker

