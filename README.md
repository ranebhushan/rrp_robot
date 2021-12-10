# RRP Robot in Gazebo

### Dependencies

To use this robot in Gazebo, you need to install the following ROS packages:-

```
sudo apt-get install ros-noetic-ros-control ros-noetic-ros-controllers ros-noetic-gazebo-ros-pkgs ros-noetic-gazebo-ros-control
```

## Usage Guidelines
- Launch the RRP robot manipulator in Gazebo using by the following command:
```
roslaunch rrp_gazebo gazebo.launch
```

- Once the robot is successfully spawned in Gazebo, open a new terminal and launch the effort controller node and the joint state publisher by using the command:
```
roslaunch rrp_control rrp_effort_control.launch
``