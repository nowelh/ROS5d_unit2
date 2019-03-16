ROS5d_unit2

How to create package :cd 
1. in ws/src =>  catkin_create_pkg tuto01 std_msgs rospy roscpp
2. in ws     =>  catkin_make
3. cd src/tuto01/src ;  vi simple_topic_publisher.py  
4. chmod +x simple_topic_publisher.py
5. mkdir ws/src/tuto01/launch ; cd ws/src/tuto01/launch
6. vi simple_topic_publisher.launch   (package = tuto01 and type = simple_topic_publisher.py)
7. roslaunch tuto01 simple_topic_publisher.launch



