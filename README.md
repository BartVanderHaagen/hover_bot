## About hover_bot
This is a follow up on the Hoverboard hack done in ROS Melodic by Emanuel Feru. 

more info about the project : github.com/EFeru

## goals
This innovative project aims to provide a simple, cost-effective, and educational experience for robot enthusiasts of all levels.

## Installation
create your workspace and source directory

git clone https://github.com/ros-teleop/twist_mux.git
git clone https://github.com/BartVanderHaagen/hover_bot.git

colcon cuild --symlink-install

## usage
ros2 launch hover_bot rsp.lanch.py

for the simulator 

ros2 launch hover_bot rsp.lanch.py use_sim_time:=true





