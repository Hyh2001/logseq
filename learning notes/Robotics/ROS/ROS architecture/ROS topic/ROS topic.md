ROS topic is a message bus or path, each topic has a name. It has several terminal commands to help users workin on [[ROS topic]].  There is also a tool called [[Rqt_graph]] to help us better understanding relationships between nodes and topics. The commands are as follow
# rostopic
	# 1. To see the available sub-commands
	rostopic -h 
	# 2. Display bandwidth used bu topics 
	rostopic bw
	# 3. Print message to screen
	rostopic echo [name]
	# 4. Display publishing rate of topics 
	rostopic hz
	# 5. Print information about active topics 
	rostopic list
	# 6. publish data to topic 
	rostopic pub topic msg_type arts
	# 7. print topic type 
	rostopic type