The data that going through the [[ROS topic]]s. The type of messgae transferred through a topic should match type defined in [[publisher node]] and [[subscriber node]]. To see the message type, use [[ROS topic]], 
```terminal
	rostopic type
``` 
command at first. Then use the result of it as
```terminal 
	rosmsg show name
```
# build own message type 
We can also build our own message types. The implementation is as follow: 
1. write a [[msg file]], 