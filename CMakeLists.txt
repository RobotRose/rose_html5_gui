cmake_minimum_required(VERSION 2.8.3)
project(rose_html5_ui)

find_package(catkin REQUIRED COMPONENTS
  actionlib
  actionlib_msgs
  rose_ui_item_selector
  rose_ui_map_display
  rose_ui_script_selector
  rosbridge_library
  rosbridge_server
  roscomm
  rose_joystick
  rospy
  rose_shared_variables
  web_video_server
)

catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
