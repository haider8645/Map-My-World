# WhereAmI

Description: This is an exercise project as part of the Robotics Software Engineer Nano Degree Program

Usage:

1) Make sure all dependencies are installed

2) Build the workspace using catkin_make

3) Source the setup.bash file from the devel folder. The devel folder is autogenerated at the workspace root folder

4) run the launch files from the my_robot and where_am_i packages

	**roslaunch my_robot world.launch**
	
	**rosrun teleop_twist_keyboard teleop_twist_keyboard.py**
 
	**roslaunch map_my_world mapping.launch**

6) Afterwards use the keyboard to guide the robot around in the world

