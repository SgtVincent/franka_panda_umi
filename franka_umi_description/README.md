# Franka Umi Robot Description

This project contains the URDF (Unified Robot Description Format) description files for a Franka robot with a UMI hand. It includes the necessary configuration, launch files, and meshes for the robot.

## Structure

- [`CMakeLists.txt`](CMakeLists.txt): The CMake file for building the project.
- [`config/`](config/): Contains configuration files for the gripper and robot settings.
- [`launch/`](launch/): Contains ROS launch files for displaying the robot.
- [`meshes/`](meshes/): Contains STL files for the robot's hand and fingers.
- [`robots/`](robots/): Contains URDF and XACRO files for the robot and its components.
- [`textures/`](textures/): Contains texture files.

## Building
Assume you have this repo inside your catkin workspace, to build the project, run the following command in your catkin root:

```sh
catkin_make
# or 
# catkin build franka_umi_description
```

## Visualization

To visualize the robot in RViz, use the following command:

```sh
roslaunch franka_umi_description display.launch
```
