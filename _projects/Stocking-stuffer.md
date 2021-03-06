---
layout: project
title: Baxter Stocking Stuffer
date: December 2014
image: http://i1380.photobucket.com/albums/ah164/aturchina0528/portfolio/newbaxter_zpstf8fg9e5.png
---

## Overview
This project involved using a [Baxter robot](http://www.rethinkrobotics.com/baxter/) to do object recognition and tag tracking (QR and barcode type) to place objects in desired locations. The project team gave it a Christmas theme with stockings and presents. Programming for this project was done in python and utilized [ROS](http://wiki.ros.org/ROS/Introduction) (robot operating system) for communication with the Baxter robot.

Complete information and repository can be found [here](https://github.com/ChuChuIgbokwe/ME495-Final-Project-Baxter-Stocking-Stuffer)  

**_Demonstration Video_** 

<iframe src="https://player.vimeo.com/video/114372776" width="500" height="283" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p></p>



### About Baxter
Baxter has two 7 degrees of freedom (DOF) arms, a 360 degree sonar and front camera, and interchangeable end-effectors. Baxter is commonly seen in industrial manufacturing settings and is advertised as an intelligent robot that learns from interaction and works safely among humans. The Baxter robot that was used in this project is a research version that allows programming through ROS.

### Project outline
Baxter was given four different color objects (presents) on a table in front of it and four locations (stockings) for these objects to the side of the robot. The robot has a two finger gripper and a camera located in the wrist. This camera was used to capture images for color recognition and tag identification.

### Step by step
* Scan the stocking area
  * Move the arm so that the camera can view all of the stocking's tags

* Identify a stocking that needs a present
  * Each stocking has a tag above it with information of what present is needed

* Scan the table in front of Baxter
  * Using color recognition, locate present corresponding to the stocking

* Grasp present and move to stocking

* Drop present into stocking

* Update list of stockings and presents
  * After a stocking is filled, remove it's tag ID from the search list

* Scan the stocking area for next empty stocking and repeat

