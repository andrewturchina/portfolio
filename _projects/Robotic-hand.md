---
layout: project
title: Robotic hand
date: March 2015
image: http://i1380.photobucket.com/albums/ah164/aturchina0528/portfolio/handapril_zpsjdkxwxfp.jpg
---

## Overview

As part of an independent project in the spring of 2015, I designed, manufactured, and implemented controls onto a robotic hand. This project was very fun and engaging as it required both mechanical design, manufacturing, and microcontroller programming.

### About robotic hands
Robotic hands are a version of an end effector or gripper and are used in a wide range applications such as grasping, pushing, pulling, sensing, and interacting with the environment. Currently the human hand is the most effective end effector because of its great dexterity and senses. Many robotic end effectors fall short of the capabilities of a human hand for a variety of reasons, however there is great research being done in this field.  

### Project outline
I was interested in studying robotic hands and the manipulation of objects through an advanced end effector. After researching different types of end effectors I decided on an under actuated model, where the system has a lower number of actuators than degrees of freedom. In the picture at the top, the hand has 4 total actuators to control the fingers.  This means that one actuator will control all three joints in a finger. An advantage of this is that the gripper is very flexible and can form around objects of different shapes and sizes without a large number of controls.  

### Step by step

* Research end effectors and evaluate strengths and weaknesses  

* Specify control method and actuators  
  * I used a microcontroller along with servo motors  

* Model, design, and prototype  
  * Start simple, test, and redesign  

![prototype](http://i1380.photobucket.com/albums/ah164/aturchina0528/portfolio/handearly_zpsb4xkfqjn.jpg)

* Implement controls
  * Write programs to accomplish specific tasks
  * Make it user friendly to interact with via computer prompts

* Advanced controls
  * Use of a [Leap Motion](https://www.leapmotion.com/) 3D controller that tracks human hand and joint position
  * Take this information to use your hands to have the robotic hand mimic your motion
  * Translate data from the Leap Motion to send commands to the robotic hand

![leap_generic](http://i1380.photobucket.com/albums/ah164/aturchina0528/portfolio/leap_zpsffsbhvyh.jpg)

![leap_motion](http://i1380.photobucket.com/albums/ah164/aturchina0528/portfolio/leapmotion_zpsavi4q1yd.png)
