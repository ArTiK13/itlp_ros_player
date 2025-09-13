cmake_minimum_required(VERSION 3.0.2)
project(itlp_ros_player)

find_package(catkin REQUIRED COMPONENTS
  rospy
)

catkin_package()

include_directories()

catkin_install_python(PROGRAMS
   scripts/gt_for_itlp.py
   DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
 )
 