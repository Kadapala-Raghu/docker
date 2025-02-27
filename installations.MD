Versions means --> TAGS

if no version mentioned to isntalled, It will install latest version

###
sudo dnf -y install dnf-plugins-core

sudo dnf config-manager --add-repo https://download.docker.com/linux/rhel/docker-ce.repo

sudo dnf install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

sudo systemctl enable --now docker

sudo systemctl start docker

sudo systemctl status docker 

------------

Afer your installation, there will be docker group created by default. So that you have to add the user into the docker group

$ usermod -aG docker ec2-user

terminology 

Virtual Machine -> AMI

Docker -> Image 

AMI => BaseOS + App runtime + User/Folder createion, COnfiguration files CODE and dependancies services

IMAGE =>


docker ps # Displays running containers

docker 




```
$ docker search <name-of-image>

$ docker info ### how many docker running , contaners

$ docker images # To check how many images

$ docker ps 

$ docker pull node ## it will pull and extraacting

$ docker pull nodejs:20-buster # buster is specific tag

$docker run ## Creating contaner from image

$ docker run -d --name sonar-test -p 9000:9000 sonarqube:lts-communitu

--name name of container
-d omited 
-p server-port

ABove command, it wll look image from locally, if not there, it will directly pull it from the docker hub


$ 




