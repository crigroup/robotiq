cmake_minimum_required(VERSION 2.8.3)
project(robotiq_description)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY meshes models urdf worlds
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
