---
title: "Robotic Path Planning for Beating Heart Surgery - MATLAB"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/portfolio_1.png'>"
collection: portfolio
---

This repository [Link](https://github.com/changh95/MATLAB-Robot-Path-Planning) includes MATLAB codes for robotic path planning of a PUMA robot using Robotics Toolbox by Peter Corke [Link](http://petercorke.com/wordpress/toolboxes/robotics-toolbox). The purpose of this code was purely for academic coursework, and may not represent the complexity of real-world situations. The coursework context assumes that the programmer is performing path planning for PUMA robot to perform beating heart surgery.

**Used software:**
* MATLAB 2016b
* Robotics Toolbox v10
* Images captured using MATLAB 2018b.

**Pre-Requisites**
trajectory_data.mat is provided prior to any programming.

-----------------

Task 1
====
Build a PUMA robot and move the end-effector to follow a linear trajectory along a sphere.

![alt text](https://github.com/changh95/MATLAB-Robot-Path-Planning/blob/master/1.png?raw=true)

![alt text](https://github.com/changh95/MATLAB-Robot-Path-Planning/blob/master/1_2.png?raw=true)

Task 2
====
Ensure that the end-effector is always perpendicular to the sphere surface.

![alt text](https://github.com/changh95/MATLAB-Robot-Path-Planning/blob/master/2.png?raw=true)

![alt text](https://github.com/changh95/MATLAB-Robot-Path-Planning/blob/master/2_2.png?raw=true)

Task 3
====
Repeat steps 1 and 2 keeping a constant velocity of the end-effector of 0.1m/s for a time-varying trajectory due to the sphere changing its size (is beating!)

![alt text](https://github.com/changh95/MATLAB-Robot-Path-Planning/blob/master/3.png?raw=true)

![alt text](https://github.com/changh95/MATLAB-Robot-Path-Planning/blob/master/3_2.png?raw=true)
