# AstraPro-RTAB-Map
Custom Launch files for Orbbec Astra Pro to work with RTAB-Map


1- cd ~/catkin_ws/src 
2- git clone https://github.com/WardBarakat/AstraPro-RTAB-Map.git 
3- read readme 
4- sudo apt-get install ros-indigo-rtabmap-ros or kinect instead
5- roslaunch astra_pro_rtabmap astrapro.launch
6- roslaunch rtabmap_ros rtabmap.launch rtabmap_args:="--delete_db_on_start" 
