cmake_minimum_required(VERSION 3.0.2)
project(bufalo_control)

find_package(catkin REQUIRED COMPONENTS
  controller_manager
  diff_drive_controller
  joint_state_controller
  bufalo_description
  robot_localization
  robot_state_publisher
)

catkin_package()

include_directories(
  ${catkin_INCLUDE_DIRS}
)
