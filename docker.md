#Reboot all containers

docker restart $(docker ps -a -q)
