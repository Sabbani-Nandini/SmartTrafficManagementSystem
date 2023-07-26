# SmartTrafficManagementSystem
In current scenario one of the serious concern
for people in smart cities such as Delhi, Bangalore, Mumbai,
Hyderabad etc. is traffic congestion. This has turned out to be
a daily problem in current time. Due to this road congestion
accidents in the city have are raised to a great extent so lives
lost due to accidents are even more crucial. Due to this
congestion on the roads, emergency vehicles such as
ambulances, fire-cars and other vehicles cannot reach on time.
This results in huge loss of life. To tackle these issues up to a
great extent we present a solution in this paper.  This can
save their time expansion for reaching the proposed
destination and can prevent the loss of human life up to great
extent. IoT provides a method to tackle these issues by
providing smart and intelligent traffic management system. 
In this project we use IR sensors to detect the density of
vehicles in each lane and based on the count signal is given to each lane 

![image](https://github.com/Sabbani-Nandini/SmartTrafficManagementSystem/assets/93151923/dab8df60-0d8f-4f21-9e17-5a0d98f64336)



# Setting up connections with Raspberry PI
we will connectcomponents such as IR sensor, Traffic Light Led to the raspberry pi Now will will connect the IR sensors and the Traffic Light LED with the Raspberry Pi according to the table:

![image](https://github.com/Sabbani-Nandini/SmartTrafficManagementSystem/assets/93151923/4c51d074-b63f-4164-95e1-e1eff4193f8b)
![image](https://github.com/Sabbani-Nandini/SmartTrafficManagementSystem/assets/93151923/ae8cc58f-dbbd-4b91-a1f2-bae020b77111)
![image](https://github.com/Sabbani-Nandini/SmartTrafficManagementSystem/assets/93151923/f8c0f432-b7c2-41b8-b181-cd29fc522b1b)
![image](https://github.com/Sabbani-Nandini/SmartTrafficManagementSystem/assets/93151923/24a9aca3-0fca-408e-be79-71349c51d1a4)








Steps to install python:
# 1. Update the Raspbian
Update the Raspbian before installing python.

sudo apt-get update

# 2. Prerequisites
Before installing Python 3.8 there are some dependencies that we need to install. Use
the following command to install the required dependencies.

sudo apt-get install -y build-essential tk-dev libncurses5-dev libncursesw5-dev
libreadline6-dev libdb5.3-dev libgdbm-dev libsqlite3-dev libssl-dev libbz2-dev
libexpat1-dev liblzma-dev zlib1g-dev libffi-dev tar wget vim
# 3. Download Python
You can download Python from the official website or use the following command.

wget https://www.python.org/ftp/python/3.8.0/Python-3.8.0.tgz
# 4. Install Python 3.8
Now we will extract and install Python from the source.

sudo tar zxf Python-3.8.0.tgz
cd Python-3.8.0
sudo ./configure --enable-optimizations
sudo make -j 4
sudo make altinstall
# 5. Check Python version
Now Python is installed you can check the version using the following command.

python3.8 -V
# 6. Make Python 3.8 as the default version
If you want to use python 3.8 as a default version you can create an alias.

echo "alias
python=/usr/local/bin/python3.8" >> ~/.bashrc
Then source the .bashrc file.
source ~/.bashrc
# 7. Check Python Version
After creating an alias check the python version again.

python -V
Python 3.8.0
Now you have successfully installed Python 3.8 on Raspberry Pi.
# 8. Clean up
Now you can clean up using the archive
sudo rm -rf Python-3.8.0.tgz
sudo rm -rf Python-3.8.0
Then open Thonny Python IDE with the help of the below steps

![image](https://github.com/Sabbani-Nandini/SmartTrafficManagementSystem/assets/93151923/622896e0-c5b0-454d-b59d-01ad062292fb)

![image](https://github.com/Sabbani-Nandini/SmartTrafficManagementSystem/assets/93151923/8859363d-4094-43ca-b476-784737149dea)

Now you are ready to run the code and run it 


