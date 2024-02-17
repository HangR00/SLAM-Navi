# How to use?

## 1.Clone the repository

Clone the repository and make sure all files are in a ros workspace,then use 'catkin_make' instruction to compile the project.

## 2.SLAM

### Run the following instructions in order:

roslaunch robot_gazebo sim_bringup.launch

roslaunch robot_navigation slam_gmapping.launch

roslaunch robot_teleop robot_teleop.launch

rosrun map_server map_saver -f myhouse

## 3.Navigation

### Run the following instructions in order:

roslaunch robot_navigation navigation.launch
