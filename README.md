# docker
Installation of Docker on PopOS 19

Open terminal and type:
$ sudo apt install apt-transport-https ca-certificates curl software-properties-common

$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

$ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu disco stable"

$ sudo apt-cache search docker-ce

$ sudo apt install docker-ce

$ docker --version
Docker version 19.03.3, build a872fc2f86

go to https://hub.docer.com and search for whalesay
copy the Docker Pull Command:  docker/whalesay

$ sudo docker run docker/whalesay cowsay Blah-Blah-Blah

run this command to see what containers are running:
$ docker ps
$ docker ps -a

to stop a container:
$ docker stop dockername

to remove a contaienr:
$ docker rm dockername
(this should print the name back)

do see the images:
$ docker images

to remove the image:
$ docker rmi dockername


