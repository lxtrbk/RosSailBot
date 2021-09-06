# Dependencies

- ROS Melodic for Raspian Buster
- ROS Libs: rosserial rosserial_arduino
	rosinstall_generator desktop rospy roscpp std_msgs gps_common visualization-msgs rosserial rosserial_arduino --rosdistro melodic --deps --wet-only --tar > melodic-custom_ros.rosinstall
