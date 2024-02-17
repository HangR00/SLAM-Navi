# 1.SLAM

roslaunch robot_gazebo sim_bringup.launch

roslaunch robot_navigation slam_gmapping.launch

roslaunch robot_teleop robot_teleop.launch

rosrun map_server map_saver -f myhouse

# 2.SLAM

roslaunch robot_navigation navigation.launch
