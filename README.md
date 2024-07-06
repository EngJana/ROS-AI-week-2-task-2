# ROS-AI-week1-task-2
ROS & AI week 1 
task 2: manipulate with turulesim package in ROS noetic and ROS2 foxy

# Turtle Movement using Keyboard
## ROS noetic:
1-	Install the turtlesim package:
- $ sudo apt-get update
- $ sudo apt-get install ros-noetic-turtlesim
2-	Initialize ROS
- $ source /opt/ros/noetic/setup.bash
- $ source ~/.bashrc
3-	Launch the Turtlesim Node
- $ roscore
- $ rosrun turtlesim turtlesim_node 
4-	Control the Turtle
In another teminal 
- $ source /opt/ros/noetic/setup.bash
- $ rosrun turtlesim turtle_teleop_key
This allows to move the turtle using arrow keys or other specified keys.
5-	To quit press (q)

## ROS2 foxy
1-	Install the turtlesim package:
- $ sudo apt-get update
- $ sudo apt install ros-foxy-turtlesimInitialize ROS
2-	Initialize ROS
- $ source /opt/ros/foxy/setup.bash
3-	Launch the Turtlesim Node
- $ roscore
- $ ros2 run turtlesim turtlesim_node
4-	Control the Turtle
In another teminal 
- $ source /opt/ros/foxy/setup.bash
- $ ros2 run turtlesim turtle_teleop_key
This allows to move the turtle using arrow keys or other specified keys.
5-	To quit press (q)

