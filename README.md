# ROS-AI-week-2-task-2
ROS & AI week 2 samrt methods internship  
task 2: manipulate with turulesim package in ROS noetic and ROS2 foxy

# Turtle Movement using Keyboard
## ROS noetic:
1. Install the turtlesim package: $ sudo apt-get install ros-noetic-turtlesim
2. Initialize ROS: $ source /opt/ros/noetic/setup.bash then $ source ~/.bashrc
3. Launch the Turtlesim Node: $ roscore
4. in another terminal: $ rosrun turtlesim turtlesim_node 
5. Control the Turtle: In another teminal Initialize ROS $ source /opt/ros/noetic/setup.bash 
6. To allows the turtle to move using arrow keys or other specified keys: $ rosrun turtlesim turtle_teleop_key
7. To quit press (q)
<img width="745" alt="ros1turtule" src="https://github.com/EngJana/ROS-AI-week-2-task-2/assets/173661625/87acf9ea-8530-404b-9661-347c662d4ee4">


## ROS2 foxy
1. Install the turtlesim package: $ sudo apt install ros-foxy-turtlesimInitialize ROS
2. Initialize ROS: $ source /opt/ros/foxy/setup.bash
3. Launch the Turtlesim Node: $ roscore
4. in another terminal: $ ros2 run turtlesim turtlesim_node
5. Control the Turtle: In another teminal Initialize ROS $ source /opt/ros/foxy/setup.bash
6. To allows the turtle to move using arrow keys or other specified keys: $ ros2 run turtlesim turtle_teleop_key
7. To quit press (q)
<img width="767" alt="ros2turtule" src="https://github.com/EngJana/ROS-AI-week-2-task-2/assets/173661625/15e4a23e-a008-4765-bcb2-454b5296f395">
