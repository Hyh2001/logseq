The ROS Service has Request/Reply mechanism. It is used between [[server node]] and [[client node]]. [[client node]] will require ROS service offered by [[server node]] with arguments and may receive some responds. There are several commands used for us to get information and modify services in terminals.
# rosservice
```Terminal
	# 1. show all the services 
	rosservice list 
	# 2. find out the type of a services 
	rosservice type [name]
	# 3. call a service 
	rosservice call [name] [args]
```
