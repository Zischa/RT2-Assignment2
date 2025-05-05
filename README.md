# RT2-Assignment2

This repository contains the source code and configuration for **RT2 Assignment 2**, part of the Robotics and Intelligent Systems course. The project focuses on developing and integrating ROS-based nodes to control a robot in a simulated environment.

## Project Overview

The assignment involves creating a ROS architecture that includes:

- **User Input** - accepts goals from the user
- **Navigation** - tracks the robot position on a live plot
- **Action Feedback** - monitors goal status (reached/not reached)
- **State Publisher** - publishes nearest obstacle distance


## Requirements

- ROS Noetic (or compatible ROS version)
- Gazebo
- Python 3
- ROS packages: [assignment_2_2024](https://github.com/CarmineD8/assignment_2_2024.git)

### Functionalitis
It's possibile for the user to send the goal by choosing a value x and y (min: -8, max: +8) and clicking the button "Send Goal" and it's possible to cancel it using the button "Cancel Goal". 
The user can choose to plot a table in which is shown the number of reached and unreached goals by clicking on "Show Goal Results"
While "Show Obstacle Distance" print on a FloatTextBar the distance from the robot to the nearest obstalce.



