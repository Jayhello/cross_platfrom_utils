cmake_minimum_required(VERSION 3.6)
project(cross_platfrom_utils)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(cross_platfrom_utils ${SOURCE_FILES})