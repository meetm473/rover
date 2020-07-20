# rover
A ROS package containing files required to visualise a Mars rover in RViz and Gazebo. This package is a dependency for [rover_control][1]. 

### About the rover design
The rover has a **rocker-bogie** mechanism. More information about why this mechanism was chosen can be found [here][2]. For the CAD model, [this][3] design has been referenced.

![Rover in SW](https://github.com/meetm473/rover/blob/master/multimedia/rover_sw.png)
![Rover in Gazebo](https://github.com/meetm473/rover/blob/master/multimedia/rover_gazebo.png)

### Commands
To view the rover in RViz
```
roslaunch rover display-rviz.launch
```
To view just the world in Gazebo
```
roslaunch rover scene-display.launch
```
To view the rover in Gazebo world
```
roslaunch rover rover.launch
```

[1]:https://github.com/meetm473/rover_control
[2]:https://en.wikipedia.org/wiki/Rocker-bogie
[3]:https://grabcad.com/library/nasa-designed-rocker-bogie-rover-1
