# Disclaimer
This project isn't complete, and also not general enough. It only works for my own dirver now.
However, the project can still be modified to your own usage if you understand this project enough.

# Introduction
This project is dedicated to create a ROS Control tool that you can control your physical robot with ease. 

You can see I use a metapackage for this project. There are mainly two parts. 
The main part is **simple_ros_control_main** package, which I use a submodule in this project.
Other packages can be treated as another part.

The main idea is that all the ROS control works are in the **simple_ros_control_main**, 
while all the custom settings are in the remaining packages.
More clearly, whenever **simple_ros_control_main** updates, you don't have to change the custom settings to fit


