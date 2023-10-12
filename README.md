# Difference-between-ROS1-and-ROS2
## First Difference 
+ ROS1: Master-Slave vs Distributed Network Architecture ROS1 communication based on Master-Slave communication.where one computer/robot should serve as ROS Master while the others serve as slaves. If ROS Master fails, the whole network fails.

+ ROS2: Data Distribution Service (DDS) that does not require ROS Master. More suitability for distributed system or multi-robot system.

## Second Difference in security
+ ROS1 is not designed for high-security application.
+ ROS2 provides some security features such as authorization.

## Third Difference in Build System
+ The build system in ROS1 is catkin.
+ The build system in ROS2 is colcon.

## Fourth Difference in Launch File
+ Launch file in ROS1 is written in XML.
+ In ROS2, a launch file can be written either in Python, XML, or YAML.

## Fiveth Difference in Non-real-time vs Real-time
+ ROS1 is not designed to be a real-time system.
+ ROS2 can be used for real-time performance.
