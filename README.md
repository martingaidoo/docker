# docker


sudo docker-compose up -d

docker ps -a


docker-compose down 

docker-compose stop
docker-compose start

docker stop $(docker ps -q) //para todos los contenedores

docker rm $(docker ps -aq) //borra todos los contenedores



sudo lsof -i :3050 //veo lo que se usa en ese puerto

