# install-ros-in-jetson-nano

1-Open a new terminal by pressing Ctrl + Alt + t or executing the “Terminal” application using the Ubuntu launch system.
2- Set up the Jetson Nano to accept software from packages.ros.org


$ sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu 

$(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'


3-Add a new apt key:

$ sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654

4-Update the Debian packages index:

$ sudo apt update


5-Install the ROS Desktop package, including support for rqt, rvizand other useful robotics packages:

$ sudo apt install ros-melodic-desktop



![image](https://user-images.githubusercontent.com/107868423/182657742-27c43bf6-5933-41f0-9dc1-70cbfb073162.png)
![image](https://user-images.githubusercontent.com/107868423/182657818-55d4d8eb-fb92-4015-9444-8d2803392457.png)

