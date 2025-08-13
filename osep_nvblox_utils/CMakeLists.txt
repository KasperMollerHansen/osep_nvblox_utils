cmake_minimum_required(VERSION 3.8)
project(osep_nvblox_utils)

find_package(ament_cmake REQUIRED)

# If you have launch files or scripts, you can install them like this:
install(DIRECTORY launch/
  DESTINATION share/${PROJECT_NAME}/launch
)

ament_package()
