# How to use
## Compile and Setup
```
source /opt/ros/noetic/setup.bash
cd catkin_ws
catkin_make
source devel/setup.bash
roscore &
```
# Options
## Launch Robot
```
cd src/lab_3/launch
roslaunch lab_3_robot.launch
```
## Launch Robot, Map, and Bag
```
cd src/lab_3/launch
roslaunch lab_3.launch
```