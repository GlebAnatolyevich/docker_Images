## Установка на корабле используя github

sudo docker build -t mynginx  github.com/GlebAnatolyevich/docker_images -f mynginx/Dockerfile
  

Атоперезапуск 
sudo docker update --restart always vigilant_zhukovsky


Создание контейнера
sudo docker start 679bc3a61761

Вход с оболочкой bash
 sudo docker exec -it vigilant_wright bash

Автоподъем контейнера


Ошибка tun
Appears when centos runs ./*.sh

The TUN device is not available 
You need to enable TUN before running this script

Solution
------
cd /dev
mkdir net
mknod net/tun c 10 200
chmod 0666 net/tun
------

---openVPN---
https://blog.sedicomm.com/2018/02/06/kak-ustanovit-i-nastroit-openvpn-server-na-debian-9-za-5-minut/
_______________
