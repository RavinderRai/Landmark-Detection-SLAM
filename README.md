# Landmark-Detection-SLAM

This project tracks the movement of a robot, using sensory data to estimate the robots position based on its distance from other notable landmarks positions. The idea is to create a world with a robot and landmarks, where the initial robots location will be fixed and the landmarks positions will be randomized. Then motion and sense functions will be used to iteratively update the positions of the robots and landmarks. We then use the collected data of the robot and landmarks positions to approoximate their locations.
While this project is written in Python, the methodology used here heavily relies on linear algebra, and an understanding of vectors, matrix multiplication, 
and matrix transformations will be necessary. 

## Python Libraries required
Standard python libraries such as numpy and matplotlib.pyplot will be needed, along with the package seaborn, which is a visualiztion package used to help understand the world that we create.

### Installation
To install any library, just use the pip install function, for example:
$ pip install Pillow

This will work for windows, mac and linux. For othe libraries, replace 'Pillow' with the name of the other library to be download.

### Author(s)

Ravinder Rai

### Acknowledgments
This project originates from the Computer Vision Nanodegree offered by Udacity. 
