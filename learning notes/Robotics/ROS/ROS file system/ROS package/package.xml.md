It is also called package manifest. This file mainly contains the package dependencies, information, and so forth.  
The structure and the information contained in this file can be shown as below. There are four main parts: description, maintainer, license and dependencies. The dependencies can be divided into build dependency and execution dependency. ==what are there differences?==
# structure and information
## description
	<description>The information </description>    
	<!-- description tag is for offering the information of the package -->
## maintainer 
	<maintainer email = "">maintainer name</maintainer>
	<!-- maintainer tag is to denote the maintainer of this package. There can be multiple maintainers. -->
## license
	<license>licnese</license>
	<!-- this denotes the open source license-->
## dependency
### build dependency
	<build_depend>roscpp</build_depend>
	<build_depend>rospy</build_depend>
	<build_depend>std_msgs</build_depend>
#### build tool dependency
	<buildtool_depend>catkin</buildtool_depend>
### execute dependency 
	<exec_depend>roscpp</exec_depend>
	<exec_depend>rospy</exec_depend>
	<exec_depend>std_msgs</exec_depend>