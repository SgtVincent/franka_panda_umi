# Franka Panda Umi Robot Description MoveIt Configuration

This repository contains two ROS packages:

1. `franka_umi_description`: This package contains the URDF (Unified Robot Description Format) description files for a Franka robot with a UMI hand. It includes the necessary configuration, launch files, and meshes for the robot.

2. `panda_umi_moveit_config`: This package contains the configuration and launch files for using the Franka robot with the MoveIt Motion Planning Framework.

## Project Structure

- [`franka_umi_description/`](franka_umi_description/): Contains the URDF description files for the Franka robot with a UMI hand.
- [`panda_umi_moveit_config/`](panda_umi_moveit_config/): Contains the configuration and launch files for using the Franka robot with the MoveIt Motion Planning Framework.

## Building

Assume you have this repo inside your catkin workspace, to build the project, run the following command in your catkin root:

```sh
catkin_make
# or 
# catkin build
```

## Visualization

To visualize the robot in RViz, use the following command:

```sh
roslaunch franka_umi_description display.launch
```

To visualize and manipulate the robot in gazebo, use the following command:

```sh
roslaunch panda_umi_moveit_config demo_gazebo.launch
```


## MoveIt Configuration

To use the MoveIt configuration for the Franka robot, refer to the launch files in the `panda_umi_moveit_config/launch/` directory.

## License

This project is licensed under the BSD License.