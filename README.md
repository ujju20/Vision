# Vision-

**An Autonomous Bot Based On Image processing And Breadth-First Search Path Finding Algorithm.**

This project is based on the instructions given in the following [Problem Statement]().

![Arena image](https://github.com/ujju20/Vision-/blob/main/test.png)

# Installation Guidelines

Along with this repository, it is needed to have the following repository:

[Vision_Arena](https://github.com/Robotics-Club-IIT-BHU/Vision-2.0-2020-Arena)

Follow the steps given in these repositories and install the packages required.

You can run [Solution.ipynb](https://github.com/ujju20/Vision/blob/main/Solution.ipynb) on the terminal.

# Approach

1.The arena was converted into a 2D matrix using image processing techniques where a particular node number denoted each square of the arena.

2.Breadth-First Search Path Finding Algorithm was used to determine the shortest path to the destination node.

3.Nodes were inserted into the list on a priority basis to prefer the inner path.

4.We used the differential drive to run the bot more efficiently

# Features

1.Visual representation of the arena and the bot movements were done using PyBullet.

2.Image processing techniques were used to manipulate the data, i.e., shape, colour and aruco marker detection in the programmable form.

3.Breadth-First Search Path Finding Algorithm determined the shortest path to reach the destination node
