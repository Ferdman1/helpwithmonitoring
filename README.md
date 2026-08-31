# helpwithmonitoring

## This is docker + docker-compose to use in astra linux
sudo apt install docker.io

sudo usermod -aG docker $USER

newgrp docker

docker ps

#### for docker 18.09.7
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
