cmake_minimum_required(VERSION 2.8.3)
project(squirrel_waypoint_msgs)

## Find catkin macros and libraries
find_package(catkin REQUIRED COMPONENTS
  geometry_msgs
  message_generation
  diagnostic_msgs
  geometry_msgs
  std_msgs
)

#add_message_files(
#  FILES
#)

## Generate services in the 'srv' folder
add_service_files(
  FILES
  ManipulationWaypointService.srv
  ExamineWaypoint.srv
)

#add_action_files(
#  FILES
#)

## Generate added messages and services with any dependencies listed here
generate_messages(
   DEPENDENCIES
   diagnostic_msgs
   geometry_msgs
   std_msgs
)

## Declare a catkin package
catkin_package(
   CATKIN_DEPENDS 
	message_runtime 
	std_msgs 
	geometry_msgs
	diagnostic_msgs
)

###########
## Build ##
###########

include_directories(
  ${catkin_INCLUDE_DIRS}
)
