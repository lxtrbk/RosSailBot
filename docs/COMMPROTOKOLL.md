## Communication with Arduino

Servopositions (INPUT): std_msgs/UInt16MultiArray
	msg.layout.dim[i].label is the servo number of index i as string (0-15)
	msg.data are servopositions in whole degree (0-180)

GPS Position (OUTPUT): sensor_msgs/NavSatFix
GPS Curse (OUTPUT): std_msgs/Float32
	in degree
GPS Speed (OUTPUT): std_msgs/Float32 
	in knos
	