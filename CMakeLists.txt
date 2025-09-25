cmake_minimum_required(VERSION 3.28.3)   
project(robot_programming)   


find_package(Eigen3 REQUIRED)            

add_subdirectory(src)                   
add_subdirectory(executables)             