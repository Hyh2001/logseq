# ROS GUI tools
## Rviz
### structure
![[Pasted image 20220926215850.png]]
#### 3d view point
The area to visualize the 3D data from sensors, robot transform data, 3D model data, and other kinds of 3D information
#### display panel
various kinds of sensor data
#### view panel
view the 3D view port according to the applcation
#### toolbar
Options for interacting with the 3D viewport, measuring robot position, setting the robot navigation goal, and changing camera view
#### time panel
Features information about the ROS time and elapsed time
### run
# need to run roscore first
	rosrun rviz rviz
### rqt
features options to visualize 2D data, logging topics, publishing topics, calling services
#### run 
	rosrun rqt_gui rqt_gui
#### debugging
##### rqt_graph
creates a dynamic graph of what's going on in the system
##### rqt_plot
a scrolling time plot of the data published on topics
###### run
	rosrun rqt_plot rqt_plot
##### rqt_console
Attaches to ROS's logging framework to display output from nodes
##### rqt_logger_level
Allow us to change the verbosity level(DEBUG,WARN,INFO, and ERROR) of nodes as they run
###### function
By setting the logger level, you will get all messages of that priority level or higher