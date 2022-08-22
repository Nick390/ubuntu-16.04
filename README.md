# Cheat sheet ubuntu-16.04
-------
This file is made for windows users that need to mimic linodes kubernetes environment on windows 10.

How to start?
-------
1- go to https://www.docker.com/get-started/. <br>
2- Download Docker Desktop. <br>
3- Install it like any other program. <br>
4- Open Docker Desktop. <br>
5- Run powershell as administrator. <br>
6- Type $` docker pull ubuntu:16.04 ` this will start downloading an image of ubuntu:16.04. <br>
7- From Docker Desktop navigate to imges and you will see `ubuntu` there. <br>
8- Select it and run it will open new popup enter the name of the container like `ubuntu-16.04` and hit run it will start new container. <br>
9- Navigate to containers and you will find `ubuntu-16.04` container click on open in terminal. <br>

Second phase
-------
10- Type $`apt-get update`. <br>
11- Type $`apt-get install sudo` to install sudo. <br>
12- Type $`adduser [Your_User_Name]` And follow the steps. <br>
12- Type $`su -` login as root. <br>
13- Type $`usermod -aG sudo [Your_User_Name]` to add user to the list for sudo. <br>
14- Close window terminal and open it again. <br>
15- Type $`sudo apt update`. <br>
16- Type $`sudo apt install nano` so we can edit files. <br>
17- Now try $`nano` if no error the mean you are ready for the next step. <br>
18- Click `CTRL + X` to exit <br>.

Phase III
-------
19- 
