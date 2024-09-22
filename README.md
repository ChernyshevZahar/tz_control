Итоговая контрольная работа по курсу ИТ-инженер. 

Задача 1 

![image desc]("C:\Users\Захар\Desktop\tz_control\Git Push\tz_control\Скрины\задача 1.png")

Задача 2 

![image desc]("C:\Users\Захар\Desktop\tz_control\Git Push\tz_control\Скрины\задача 2.png")


Задача 3 

![image desc]("C:\Users\Захар\Desktop\tz_control\Git Push\tz_control\Скрины\задача 3.1.png")
![image desc]("C:\Users\Захар\Desktop\tz_control\Git Push\tz_control\Скрины\задача 3.2.png")

Задача 4  

![image desc]("C:\Users\Захар\Desktop\tz_control\Git Push\tz_control\Скрины\задача 4.png")


Задача 5 


1

Mkdir Kennel
cd ~/Kennel
cat > home_animals
cat > pack_animals
cat home_animals pack_animals > animals
cat animals
mv animals mans_friends
ls -ali

2

cd ..
mkdir Kennel_system
cd ~/Kennel
mv mans_friends ~/Kennel_system
cd ~/Kennel_system
ls -ali

3

sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb
sudo apt-get update
sudo apt-get install mysql-server

4

sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
sudo dpkg -r docker-ce-cli
