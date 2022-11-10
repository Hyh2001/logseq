ROS package contains all source code, data files, build files, dependencies, and other files are organized in packages
# structure
ROS package contains several components. It contains [[CMakelists.txt]], [[include folder]], [[package.xml]], [[src]], [[script]], [[msg folder]], [[srv folder]]. 
# create [[ROS package]] 
We can follow the steps and codes below to create a [[ROS package]]. 

	cd ~/catkin_ws/src
	catkin_create_pkg name [depend1] [depend2] [depend3]
	// usually the three depends are std_msgs,rospy,roscpp
	cd ~/catkin_ws 
	catkin_make
	source catkin_ws/devel/setup.bash
# reveal of dependencies of a [[ROS package]] 
ROS dependencies are stored in [[package.xml]], you can see the dependencies inside the folder. The dependencies of the package can also have dependencies which are named [[indirect dependency]], 

	// this will show the direct dependencies
	rospack depends1 name 
	// this will show all the dependencies
	rospack dependens name 
	
	