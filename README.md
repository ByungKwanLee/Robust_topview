# Robust Topview for analyzing signular value (Real-Time processing by ROS)
- **Author  : `Byung-Kwan Lee` (leebk@kaist.ac.kr)        M.S. Candidate**

## Requirements
- ROS kinetic version
- C++14

## Topic Message of system variable
- subscriber : **/camera/image_color/compressed** 
- publisher  : **/output/bird_eye**
- publisher  : **/output/bird_eye/compressed**

## Guide for Starting to 
- catkin_make && source devel/setup.bash (build for custom workspace and register into ros workspace)
- rosrun robust_topview robust_topview

## Method
- Analyzing singular value for summation reducing effect of false mathcing measurement



