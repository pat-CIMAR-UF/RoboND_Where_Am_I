# RoboND_Where_Am_I

This the project of Udacity Robotics Software Development Nanodegree **project of Localization with Adaptive Monte Carlo Localization ROS package**.

# Installation
```
$ cd (catkin_ws)/src
$ git clone https://github.com/pat-CIMAR-UF/RoboND_Where_Am_I.git
$ cd ..
$ catkin_make
```

# To Run
```
$ cd catkin_ws
$ source devel/setup.bash
$ roslaunch my_robot world.launch

# Open another terminal
$ roslaunch my_robot amcl.launch
```

# Misc
The parameters in [amcl.launch](https://github.com/pat-CIMAR-UF/RoboND_Where_Am_I/blob/master/my_robot/launch/amcl.launch) is meant to be tuned to fit in your case.

