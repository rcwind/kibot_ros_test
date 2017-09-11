cmake_minimum_required(VERSION 2.8.3)

project(kibot_nav)

find_package(catkin REQUIRED COMPONENTS dynamic_reconfigure)

catkin_python_setup()

catkin_package(CATKIN_DEPENDS dynamic_reconfigure)
