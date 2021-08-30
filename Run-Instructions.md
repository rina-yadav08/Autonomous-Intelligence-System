# Creating a new catkin workspace for this repository

**This project is carried out Kinectic Version of ROS**

### Make a new workspace for catkins.

Navigate to your new workspace's intended directory in your terminal shell and run the following commands, replacing **wsname** with the name of your new workspace.
  
  1. **$ mkdir -p *wsname*/src**
  2. **$ cd *wsname*/src/**
  3. **$ catkin_init_workspace**
  4. **$ cd**
  5. **$ catkin_make**

### Into your catkin workspace copy necessary folders.

Execute the following commands in the same **wsname** directory:

  1. **$ cd ROS-Turtlebot-Navigation-Project/**
  2. **$ cp -r src/bot ../src**
  3. **$ cp -r worlds docs project_init.sh ../**
  4. **$ cd**
  5. **$ catkin_make**

# Using an existing catkin workspace to set up this repository

### Into your catkin workspace copy necessary folders.

Execute the following commands in your catkin workspace directory:

  1. **$ cd ROS-Turtlebot-Navigation-Project/**
  2. **$ cp -r src/bot ../src**
  3. **$ cp -r worlds docs project_init.sh ../**
  4. **$ cd**
  5. **$ catkin_make**

# Code Running

### Getting the Gazebo Environment Started:

Run the following commands in a terminal to start the Gazebo world:

  1. **$ source devel/setup.bash**
  2. **$ chmod +x project_init.sh**
  3. **$ ./project_init.sh**

### Starting self-navigation to the destination:

To start the Turtlebot autonomous navigation, type the following commands in a new terminal.

  1. **$ source devel/setup.bash**
  2. **$ roslaunch bot bot.launch**




