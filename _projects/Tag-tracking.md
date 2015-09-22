---
layout: project
title: Tag Tracking
date: November 2014
image: https://raw.githubusercontent.com/andrewturchina/miniproject1/master/ar_sys_pic.png
---

## Overview

This project involved setting up and designing experiments to evaluate several tag tracking packages to assess their usefulness.  Programming for this project was done in python and utilized [ROS](http://wiki.ros.org/ROS/Introduction) (robot operating system).  

A full tutorial with details on the process of camera calibration, package installation, and complete test results can be found in [this repository](https://github.com/ablarry91/ros-tag-tracking).  

![qr_code_track](http://i1380.photobucket.com/albums/ah164/aturchina0528/portfolio/tagtrackpic_zpspnoibmag.png)


### About tag tracking
Tag tracking is a useful technique to be able to identify an object and estimate it's position and angle. Tags can store a wide range of information based on user need. It can be used in many applications including warehouse shipping and receiving, inventory counts, barcode scanning, and pose estimation. Tag tracking allows added flexibility to systems that comes with an improvement in capturing data.  

### Project outline
Three tag tracking packages were tested and compared both quantifiably and quantitatively.  We were interested in pose estimate noise, minimum and maximum tracking distance, average tracker frequency, ease of use, light sensitivity, and interruptions of visibility.  


### Step by step
* Camera calibration
  * A USB webcam was used, however others such as a Kinect may be used for better results.  
  * Creates a calibration file by sampling several photos of a known object and calculating a mean.  

       	          [Checkerboard calibration](http://wiki.ros.org/camera_calibration/Tutorials/MonocularCalibration)  
![calibration](http://i1380.photobucket.com/albums/ah164/aturchina0528/portfolio/calibration_zps21kxnbdg.png)

* Download and install tag tracking packages and dependencies
* Create launch files to nicely package image data and visual display together for ease of use

* Run experiments and analyze data for comparisons  

	Pictured below: [ar_track_alvar](http://wiki.ros.org/ar_track_alvar)  

	![ar_track_alvar](http://i1380.photobucket.com/albums/ah164/aturchina0528/portfolio/ar_track_alvar_zps1daiadgp.png)


