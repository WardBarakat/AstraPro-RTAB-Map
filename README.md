# AstraPro-RTAB-Map
Custom Launch files for Orbbec Astra Pro to work with RTAB-Map
cd ~/catkin_ws/src 
git clone https://github.com/WardBarakat/AstraPro-RTAB-Map.git 
read readme 
sudo apt-get install ros-indigo-rtabmap-ros or kinect instead
roslaunch astra_pro_rtabmap astrapro.launch
roslaunch rtabmap_ros rtabmap.launch rtabmap_args:="--delete_db_on_start" 
