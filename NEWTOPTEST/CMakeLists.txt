cmake_minimum_required(VERSION 3.15)

set(PROJECT_NAME main)
project(${PROJECT_NAME})

set(CMAKE_CXX_STANDARD 20)

add_executable(${PROJECT_NAME} main.cpp func.cpp ubed.cpp func.hpp ubed.hpp)