# ROS-installation-
how to install the Robot Operating System (ROS) 


First, you should install the Virtual Box form: https://www.virtualbox.org/wiki/Downloads

Second, install Ubuntu opearting system form: https://ubuntu.com/download/desktop

Third, you should make a virtual machine for Ubuntu inside the Virtual box and make all the process of installation for ubuntu 

Next, open the terminal and excute the following command:


1- sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list' 
2- sudo apt install curl # if you haven't already installed curl
3- curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -
4- sudo apt update
5- sudo apt install ros-noetic-desktop-full
6- source /opt/ros/noetic/setup.bash
7- sudo apt install python3-rosdep python3-rosinstall python3-rosinstall-generator python3-wstool build-essential
8- sudo apt install python3-rosdep
9- sudo rosdep init
10- rosdep update

