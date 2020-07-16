# ROS_URDF_Moving_Robot

In this project, I create a urdf two-wheel robot in Xacro(XML Macros), 
with differntial drive and a python script which allows the automation navigate. 
Also has an arm ,a camera and a lidar. The control of the arm was done with a PID controller.

## Content
* Config: Yaml file for the PID controller
* Launch: Launch files for Rviz Gazebo and the PID controller.
* Meshes: The external file which are used, in this case are the camera and the lidar.
* urdf: The robot design for Rviz and Gazebo
* worlds: The startup world the robot will launch in Gazebo
* move3.py: The navigation program

## Video Result
[ROS - Two-Wheel Differential Drive Robot](https://www.youtube.com/watch?v=nlIx-SwZfmE&feature=youtu.be)


