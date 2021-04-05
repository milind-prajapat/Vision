# Vision
A project based on image processing and path finding algorithm using pybullet as simulator

This project is based on the instructions given in the following [Problem Statement](https://drive.google.com/file/d/1gC5mwmm_vMUPtPOinPhZ4rZZTMcA5sih/view?usp=sharing).

## Installation Guidelines
Along with this repository, it is needed to have the following repository:
* [Vision_Arena](https://github.com/Robotics-Club-IIT-BHU/Vision-2.0-2020-Arena)

Follow the steps given in these repositories and install the packages required.

You can either run the code directly on visual studio using [Vision.sln](https://github.com/milind-prajapat/Vision/blob/main/Vision.sln) or can run [Solution.py](https://github.com/milind-prajapat/Vision/blob/main/Solution.py).

## Project Features
* Visual representation of the arena and the bot movements were done using pybullet.
* Image processing techniques using OpenCV was used to manipulate the data, i.e., shape, colour and aruco marker detection in programmable form.
* The arena was converted into a 2-D matrix where a particular node number denoted each square in the arena.
* Breadth First Search algorithm determined the shortest path to reach the destination node.
* The bot uses the differential drive for the movements.

## References
1. [Run on Vision-Arena](https://drive.google.com/file/d/16UYtqpRY0y2ey_q_UJsuPqzUj9xVu7Z1/view?usp=sharing)
