# RRP Robot in Gazebo

### Dependencies

To use this robot in Gazebo, you need to install the following dependencies:-

```
sudo apt-get install ros-noetic-ros-control ros-noetic-ros-controllers ros-noetic-gazebo-ros-pkgs ros-noetic-gazebo-ros-control
```

## Usage Guidelines
- To run the RRP robot in Gazebo, launch the Gazebo simulator and spawn a new robot by the following command:

```
roslaunch rrp_gazebo gazebo.launch
```

- Once the robot is successfully spawned in Gazebo, open a new terminal and launch the effort controller node and the joint state publisher by using the command:

```
roslaunch rrp_control rrp_effort_control.launch
```
