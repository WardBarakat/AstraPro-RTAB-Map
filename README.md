# AstraPro-RTAB-Map
Custom Launch files for Orbbec Astra Pro to work with RTAB-Map

1- cd ~/catkin_ws/src 

2- git clone https://github.com/orbbec/ros_astra_camera.git

3- git clone https://github.com/orbbec/ros_astra_launch.git 

4- git clone https://github.com/WardBarakat/AstraPro-RTAB-Map.git 

5- cd .. 

6- catkin_make 

7- read readme inside astra_pro_rtabmap you need to modify few launch files.

8- roslaunch astra_pro_rtabmap astrapro.launch

9- refer to http://wiki.ros.org/rtabmap_ros/Tutorials/HandHeldMapping 

10- sudo apt-get install ros-indigo-rtabmap-ros or kinetic instead

11- roslaunch rtabmap_ros rtabmap.launch rtabmap_args:="--delete_db_on_start" 
