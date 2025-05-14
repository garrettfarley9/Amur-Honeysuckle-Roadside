# Amur-Honeysuckle-Roadside
This repository contains an image classification model used to identify Amur Honeysuckle, and an RL model to move a robot with the intention to be loaded into a robot to cut Amur Honeysuckle on roadsides
##TODO
Hung - Robotics: movement, GPS, saw, construction, clamp for pulling
Garrett - R cnn bounding box model, RL model for seeking and chopping, GIS database

##Object Detection Model
This R-CNN model detects Amur Honeysuckle using a Raspberry Pi camera with lines, instead of bounding boxes?
To look up: Hough Transform
https://huggingface.co/sb3/tqc-FetchPickAndPlace-v1
https://huggingface.co/foduucom/plant-leaf-detection-and-classification/tree/main

##RL model for Robot Locomotion
This RL model uses PPO? to navigate through the world which rewards agent for displacement of stem? number of stems cut? finding Amur Honeysuckle? cutting tall/thick stems?

##Physical Robot
A continuous track wheeled robot with a saw system to cut stems built on Raspberry Pi processor and camera optimized for machine learning. Battery with solar panels? 3d printed chassis. The roadsides are usually pretty grassy and without large obstacles.

##Resources
https://www.missouribotanicalgarden.org/gardens-gardening/gardening-in-st-louis/invasives/bush-honeysuckle#19753251-cut-stem-application

https://besjournals.onlinelibrary.wiley.com/doi/full/10.1002/2688-8319.12332

https://scholar.google.com/scholar?start=60&q=lonicera+maackii+removal&hl=en&as_sdt=0,31&as_vis=1#d=gs_qabs&t=1732059072223&u=%23p%3D5sTbU7zy-tkJ

https://journalofbigdata.springeropen.com/articles/10.1186/s40537-021-00444-8

https://datascience.oneoffcoder.com/restricted-boltzmann-machine.html
