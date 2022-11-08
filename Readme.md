# Pr2 Gripper Perception Module

[![Dependency Status][Overworld-Dependency-Image]][Overworld-Dependency-Url]

This package is an Overworld object perception module using the Pr2 pressure sensors.

We advise you to install all Overworld external perception modules in a same folder (e.g. overworld_modules) in your ROS workspace.

## Installation

Here we assume Overworld to be installed.

```bash
sudo apt install ros-$ROS_DISTRO-pr2-common
cd ~/catkin_ws/src/overworld_modules
git clone https://github.com/sarthou/pr2_gripper_perception_module.git
cd ../..
catkin_make
```

[Overworld-Dependency-Image]: https://img.shields.io/badge/dependencies-overworld-yellowgreen
[Overworld-Dependency-Url]: https://github.com/sarthou/overworld