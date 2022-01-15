cmake_minimum_required(VERSION 3.5)
project(ar3_description)

find_package(ament_cmake REQUIRED)

install(DIRECTORY config gazebo launch meshes ros2_control urdf
        DESTINATION share/${PROJECT_NAME})

ament_package()
