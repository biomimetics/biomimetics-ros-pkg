biomimetics-ros-pkg
=========

Biomimetic Millisystems Lab ROS Repository.
This repository includes an imageproc ROS node.

Installation
--------------

Check out the repository:
```
cd
git clone https://github.com/andrewjchen/biomimetics-ros-pkg.git
cd biomimetics-ros-pkg
git submodule update --init
```

Install imageproc_node to the catkin workspace:
```
cd ~/catkin_ws/src/
ln -s ~/biomimetics-ros-pkg/imageproc_node
rospack profile
```

Run:
```
rosrun imageproc_node imageproc_node.py
```
