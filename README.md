# Amur-Honeysuckle-Roadside
This repository contains an image classification model used to identify Amur Honeysuckle, and an RL model to move a robot with the intention to be loaded into a robot to cut Amur Honeysuckle on roadsides

##Object Detection Model
This R-CNN model detects Amur Honeysuckle using a Raspberry Pi camera with lines, instead of bounding boxes?
To look up: Hough Transform

##RL model for Robot Locomotion
This RL model uses PPO? to navigate through the world which rewards agent for displacement of stem? number of stems cut? finding Amur Honeysuckle? cutting tall/thick stems?

##Physical Robot
A continuous track wheeled robot with pneumatic lopper system to cut stems built on Raspberry Pi processor and camera optimized for machine learning. Battery with solar panels? 3d printed chassis.
