cmake_minimum_required(VERSION 3.0.2)
project(bufalo_gazebo)

find_package(catkin REQUIRED COMPONENTS
  controller_manager
  gazebo_plugins
  gazebo_ros
  gazebo_ros_control
  bufalo_control
  bufalo_description
)

catkin_package()

include_directories(
  ${catkin_INCLUDE_DIRS}
)
