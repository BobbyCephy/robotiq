cmake_minimum_required(VERSION 2.8.3)
project(robotiq_gazebo)

find_package(catkin REQUIRED COMPONENTS 
  rospy 
  gazebo_ros
  control_toolbox
  xmlrpcpp
  roboticsgroup_upatras_gazebo_plugins
)

find_package(gazebo REQUIRED)
find_package(Boost REQUIRED COMPONENTS thread)

catkin_package(DEPENDS 
  rospy 
  gazebo_ros
  control_toolbox
  xmlrpcpp
  roboticsgroup_upatras_gazebo_plugins
)
