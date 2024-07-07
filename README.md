
## Установка на корабле используя github

sudo docker build -t mynginx  github.com/GlebAnatolyevich/docker_images -f mynginx/Dockerfile
  

Атоперезапуск 
sudo docker update --restart always vigilant_zhukovsky


Создание контейнера
sudo docker start 679bc3a61761

Вход с оболочкой bash
 sudo docker exec -it vigilant_wright bash
