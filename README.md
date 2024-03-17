# ROS2 Robotic Arm Project
## Overview
This project integrates a simple two-axis robotic arm with a mobile base using ROS2 and Gazebo, demonstrating the application of URDF, Gazebo simulation, and ROS2 communication.

# Quick Start
Dependencies: ROS2, Gazebo
Installation:
  
  colcon build 
  
  source install/setup.bash

  ros2 launch my_robot_bringup arm_and_base.launch.py
  
# Features
Two-axis robotic arm on a mobile base.
Gazebo simulation with custom plugins.
ROS2 topic-based control and RViz visualization.
