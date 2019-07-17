# Plywood Mazes
Author: Roberto Zegers R.

## Abstract
A collection of Gazebo worlds out of plywood plates for rapid and comprehensive testing of mobile robotic systems in simulation.

## Run

- Clone this repository into a ROS catkin workspace
- Source your ROS environment
- To launch Gazebo with one of the included worlds: `$ roslaunch plywood_mazes maze_1_6x5.launch`
- To spawn a Turtlebot3 robot you can use the included launch file `$ roslaunch plywood_mazes spawn_turtlebot3.launch`

## Available Worlds

+ Maze 1, 6x5 mts: maze_1_6x5.world
+ Maze 2, 6x5 mts: maze_2_6x5.world
+ Maze 3, 6x6 mts: maze_3_6x6.world

## Turtlebot 3
To add the Turtlebot3 to your workspace move the the src directory and use this command:  
`$ git clone https://github.com/ROBOTIS-GIT/turtlebot3.git`  

**Disclaimer**  
This collection of Gazebo Worlds was inspired by the robot's practice and competition area used during my attendance to the **ROS Summer School 2018** at the **Aachen University of Applied Science** in Germany.
