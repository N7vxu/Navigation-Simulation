# Navigation-Simulation

# Launch Simulation World

$ export TURTLEBOT3_MODEL=burger
$ roslaunch turtlebot3_gazebo turtlebot3_world.launch

# Run Navigation Node

$ export TURTLEBOT3_MODEL=burger
$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

# Estimate Initial Pose

$ roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
