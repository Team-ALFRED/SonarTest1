# SonarTest1
controlling turtlesim with 2 sonar sensors


To run use these commands all in a different terminal:
////////////////////////////
roscore
rosrun turtlesim turtlesim_node
rosrun rosserial_python serial_node.py /dev/ttyACM0 
rosrun turtlesim telelop_key
////////////////////////////
ACM0 could be something else like ACM1 ACM2 ...
