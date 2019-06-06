# Robotics-Software-Engineering-Nanodegree_BuildMyWorld

# Goal
Pick a place where you want to deploy your robot, for example: your apartment, your office, or your favorite restaurant. In addition, create any model of your choice and import a model from the Gazebo library.

# Summary of Tasks
1. Build a single floor wall structure using the Building Editor tool in Gazebo. Apply at least one feature, one color, and optionally one texture to your structure. Make sure there's enough space between the walls for a robot to navigate.  

2. Model any object of your choice using the Model Editor tool in Gazebo. Your model links should be connected with joints.  

3. Import your structure and two instances of your model inside an empty Gazebo World.  

4. Import at least one model from the Gazebo online library and implement it in your existing Gazebo world.  

5. Write a C++ World Plugin to interact with your world. Your code should display “Welcome to ’s World!” message as soon as you launch the Gazebo world file.  

# Project Requirements
Gazebo >= 7.0  

# Project Setup
Run Update On Linux Command Line:   
```bash
$ sudo apt-get update && sudo apt-get upgrade -y
```  


# Project Directory
 ```bash
 .Project1                          # Build My World Project  
 ├── model                          # Robot and Building Model files  
 │   ├── model.config  
 │   ├── model.sdf  
 ├── script                         # Gazebo World plugin C++ script      
 │   ├── hello.cpp  
 ├── world                          # Gazebo World containing models   
 │   ├── myworld.world  
 ├── CMakeLists.txt                 # Link libraries  
 └──                              
```

# Run Instructions
Create a workspace:    
```bash
$ mkdir -p /home/workspace/catkin_ws/src
$ cd /home/workspace/catkin_ws/src
$ catkin_init_workspace
```   

Clone this git repository in src:    
```bash
git clone https://github.com/dereklau33/Robotics-Software-Engineering-Nanodegree_BuildMyWorld.git
```  

Build package:  
```bash
source devel/setup.bash
catkin_make
```
