# 3d_drone_douteki
ガウス過程を逐次ガウス過程に変更

1: roslaunch bebop_teleop bebop_connection.launch 

2: roslaunch bebop_teleop teleop.launch 

3: roslaunch darknet_ros darknet_ros.launch 

4: rosrun kl_evaluation kl_evaluation 

5: rosrun keyboard keyboard → 1を押す 

6: roslaunch bebop_teleop slam.launch 

7: roslaunch marker_util bebop.launch 

8: roslaunch slam_util bebop.launch 

9: rosrun gaussian_py gaussian.py
