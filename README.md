# Kinova-Gen3-RealSense_Noetic

This ROS package is aimed to simulate the Kinova Gen3 arm with a RealSense D435 mounted on the end effector. 
In order to do that we have used the official package from Kinova called ros_kortex, the official ackage from RealSense called realsense2_description and a plugin for Gazebo, which simulates the RealSense camera, called realsense_gazebo_plugin.

## How to use

If want to launch the simulation without the camera open a terminal and run:
- roslaunch kortex_gazebo spawn_kortex_robot.launch

Instead if you want to launch the simulation with the camera open a terminal and run:
- roslaunch kortex_gazebo spawn_kortex_realsense_robot.launch 
