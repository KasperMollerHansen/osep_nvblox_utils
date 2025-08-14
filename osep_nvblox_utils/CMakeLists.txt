cmake_minimum_required(VERSION 3.8)
project(osep_nvblox_utils)

find_package(ament_cmake REQUIRED)
find_package(isaac_ros_nvblox REQUIRED)
find_package(osep_nvblox_boot REQUIRED)

install(DIRECTORY launch
  DESTINATION share/${PROJECT_NAME})

ament_package()