# docker-project for Launch Gogs using docker.
#first you have to install docker in your system. in my case i am using RHEL8
#for rhel8
go to browser - https://download.docker.com/linux/centos/7/x86_64/stable/
#then create a repo using it.
#for installing docker!
yum install docker-ce -y
#for start docker service
systemctl start docker
#h
#Here i used MYSQL for database.
#for download MYSQL :-
docker pull mysql:latest
#for download Gogs
docker pull gogs/gogs
docker images (run it for showing how many images you have)
#for launching it you have to download docker-compose
#after that create a directory for store the docker-compose file:-
mkdir -p /Desktop/mycompose
#then store the docker-compose file here and
docker-compose up
