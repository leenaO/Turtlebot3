What is SLAM
-------------------------

    SLAM stands for Simultaneous localization and mapping.

    it is a technology used for robot to localize its own position and construct a map in an unknown environment.

Sensors
-------------------------

SLAM uses several different types of sensors:

  •	A LiDAR-based SLAM system uses a laser sensor to generate a 3D map of its environment.

  •	Visual SLAM, typically tracks points of interest through successive camera frames to triangulate the 3D position of the camera, this information is then used to build a 3D map. 

TurtleBot3
-------------------------

    is a new generation mobile robot.

Let we use SLAM with TurtleBot! so we want to create a map of the TurtleBot environment.

To do that we will use Rviz and Gazebo on ubuntu.

Open this link https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/#pc-setup, go to the menue and choose from Quick Start Guide list > Pc setup, then do all the instructions.

after that choose Gazebo simulation then SLAM simulation from simulation list and complete the instructions.
you can do the map now!

This is my result:

![Screenshot from 2021-06-24 03-49-05](https://user-images.githubusercontent.com/46565265/123185900-a5b62b80-d49f-11eb-8789-82322feaf162.png)

