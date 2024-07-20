cmake_minimum_required(VERSION 3.5)
project(odri_bolt_description)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY meshes ros2_control urdf gazebo config rviz
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
