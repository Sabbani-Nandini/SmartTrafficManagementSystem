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
we will connectcomponents such as IR sensor, Traffic Light Led to the raspberry pi Now will will connect the IR sensors and the Traffic Light LED with the
Raspberry Pi according to the table:
Vcc of IR Sensor 1	Connect it to Breadboard
Vcc of IR Sensor 2	Connect it to Breadboard
Vcc of IR Sensor 3	Connect it to Breadboard
Vcc of IR Sensor 4	Connect it to Breadboard
Vcc of IR Sensor 5	Connect it to Breadboard
Vcc of IR Sensor 6	Connect it to Breadboard
Vcc of IR Sensor 7	Connect it to Breadboard
Vcc of IR Sensor 8	Connect it to Breadboard
Ground of IR sensor 1	Connect it to Breadboard
Ground of IR sensor 2	Connect it to Breadboard
Ground of IR sensor 3	Connect it to Breadboard
Ground of IR sensor 4	Connect it to Breadboard
Ground of IR sensor 5	Connect it to Breadboard
Ground of IR sensor 6	Connect it to Breadboard
Ground of IR sensor 7	Connect it to Breadboard
Ground of IR sensor 8	Connect it to Breadboard
Vout of IR sensor 1	Connect it with GPIO 26 (BCM 37)
Vout of IR sensor 2	Connect it with GPIO 1 (BCM 28)
Vout of IR sensor 3	Connect it with GPIO 7 (BCM 26)
Vout of IR sensor 4	Connect it with GPIO 19 (BCM 35)
Vout of IR sensor 5	Connect it with GPIO 17 (BCM 11)
Vout of IR sensor 6	Connect it with GPIO 8 BCM 24)
Vout of IR sensor 7	Connect it with GPIO 21 (BCM 40)
Vout of IR sensor 8	Connect it with GPIO 25 (BCM 22)
LED1 Red	Connect it with GPIO 2 (BCM 3)
LED1 Yellow	Connect it with GPIO 3 (BCM 5)
LED1 Green	Connect it with GPIO 4 (BCM 7)
LED2 Red	Connect it with GPIO 10 (BCM 19)
LED2 Yellow	Connect it with GPIO 9 (BCM 21)
LED2 Green	Connect it with GPIO 11 (BCM 23)
LED3 Red	Connect it with GPIO 18 (BCM 12)
LED3 Yellow	Connect it with GPIO 15 (BCM 10)
LED3 Green	Connect it with GPIO 14 (BCM 8)
LED4 Red	Connect it with GPIO 20 (BCM 38)
LED3 Yellow	Connect it with GPIO 16 (BCM 36)
LED3 Green	Connect it with GPIO 12 (BCM 32)
Common ground from breadboard	Connect it with ground of RaspberryPi
Common Vcc from breadboard	Connect it with RaspberryPi 5v


Steps to install python:
# 1. Update the Raspbian
Update the Raspbian before installing python.
sudo apt-get update

# 2. Prerequisites
Before installing Python 3.8 there are some dependencies that we need to install. Use
the following command to install the required dependencies.
sudo apt-get install -y build-essential tk-dev libncurses5-dev libncursesw5-dev
libreadline6-dev libdb5.3-dev libgdbm-dev libsqlite3-dev libssl-dev libbz2-dev
KESHAV MEMORIAL INSTITUTE OF TECHNOLOGY | Smart Traffic Light Management System 29
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
If you want to use python 3.8 as a default version you can create an alias.echo "alias
python=/usr/local/bin/python3.8" >> ~/.bashrc
Then source the .bashrc file.
source ~/.bashrc
# 7. Check Python Version
After creating an alias check the python version again.
KESHAV MEMORIAL INSTITUTE OF TECHNOLOGY | Smart Traffic Light Management System 30
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


