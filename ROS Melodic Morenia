# ROS Melodic Morenia for Ubuntu Linux

# Source List
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

# Keys
sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 421C365BD9FF1F717815A3895523BAEEB01FA116

# Install
sudo apt update

sudo apt install ros-melodic-desktop-full

# Intialize "rosdep"
sudo rosdep init
rosdep update

# Enviro Setup
echo "source /opt/ros/melodic/setup.bash" >> ~/.bashrc
source ~/.bashrc

source /opt/ros/melodic/setup.bash

# Dependencies for Package Building
sudo apt-get install python-rosinstall python-rosinstall-generator python-wstool build-essential
#source ~/.bashrc
