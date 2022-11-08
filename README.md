# SLAM + Navigation simulation for mobile robot

**Goal -->** Through this project, I build a ROS 2 simulation for a mobile robot. The program is written, tested and simulated for ROS 2 - Foxy Fitzroy. The simulation aims to complete 3 main tasks:

1. To build a robust package that can spawn a robot in a simulation world of our selection.
2. To use slam toolbox to perform SLAM in an explored environment to build an acurate 2D representation of a Gazebo World.
3. To use ROS 2 Navigation Stack (Nav 2) to move the mobile robot around the map autonomously

<!-- <p align="center">
  <img src = "Images/img5.png" width = "400" >
</p> -->

## Background

Nav2, the ROS2 Navigation Stack, is a collection of software packages that allows a mobile robot to move from a starting location to a goal location autonomously, without colliding with obstacles in the way.

The Slam Toolbox package incorporates information from laser scanners in the form of a LaserScan message and TF transforms from odom->base link, and creates a 2D map. This package will allow you to fully serialize the data and pose-graph of the SLAM map to be reloaded to continue mapping, localize, merge, etc.

## System Requirements
- Ubuntu 20.04
- ROS2 - Foxy Fitzroy Distribution
- Gazebo
- Rviz2

## RQT Graph

<p align="center">
  <img src = "media/Kazam_screenshot_000044.png" width = "610" >
</p> 


## General Setup
<p align="center">
  <img src = "media/Kazam_screenshot_00002.png" height = "250" >
  <img src = "media/Kazam_screenshot_00004.png" height = "250" >
  <img src = "media/Kazam_screenshot_00005.png" height = "450" >
</p> 

## SLAM results
<p align="center">
  <img src = "media/Kazam_screenshot_00010.png" width = "750" >
  <img src = "media/Kazam_screenshot_00009.png" width = "750" >
</p> 

## NAV 2 results

<p align="center">
  <img src = "media/Kazam_screenshot_000011.png" height = "320" >
  <img src = "media/Kazam_screenshot_000022.png" height = "320" >
  <img src = "media/Kazam_screenshot_000033.png" height = "320" >
  <img src = "media/Kazam_screenshot_00008.png" height = "450" >
  <img src = "media/Kazam_screenshot_000055.png" height = "450" >
</p> 




<!-- The final result can be found in this [Video Link](https://drive.google.com/file/d/13d53jG-qHz8MxfdAAgOHgRX02tFpSac2/view?usp=sharing)  -->

<!-- <p align="center">
  <img src = "Images/priusTake1_AdobeExpress.gif" width = "300" >
</p> -->

## Acknowledgements

 - Inspired by work done in this [Blog Article](https://automaticaddison.com/navigation-and-slam-using-the-ros-2-navigation-stack/)
 - Nav2 [Github](https://github.com/ros-planning/navigation2) and [Documentation](https://navigation.ros.org/)
 - Slam_toolbox [Github](https://github.com/SteveMacenski/slam_toolbox)
 - ROS 2 Foxy Fitzroy - [Tutorials](https://docs.ros.org/en/foxy/Tutorials.html)


## Paper References
- Macenski, Steve & Jambrecic, Ivona. (2021). SLAM Toolbox: SLAM for the dynamic
world. Journal of Open Source Software. 6. 2783. 10.21105/joss.02783.
- S. Macenski, F. Martín, R. White and J. G. Clavero, "The Marathon 2: A Navigation
System," 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems
(IROS), 2020, pp. 2718-2725, doi: 10.1109/IROS45743.2020.9341207.


## Support

<!-- *NOTE:* all file paths in the repository are absolute and they may need to updated for you personal system. Below is a list of files that may need to be corrected.
- urdf/prius.world
- world/prius_on_track_empty.world
- world/prius_on_track.world
- prius_line_following/saveVideo.py 
- launch/car_on_track.launch.py  -->

For any questions, email me at jaisharm@umd.edu
