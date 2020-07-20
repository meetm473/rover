cmake_minimum_required(VERSION 2.8.3)
project(rover)

find_package(catkin REQUIRED)
catkin_package()

if(CATKIN_ENABLE_TESTING)
  find_package(roslaunch REQUIRED)
endif()

include_directories(${catkin_INCLUDE_DIRS})

install(DIRECTORY config meshes launch urdf worlds
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
