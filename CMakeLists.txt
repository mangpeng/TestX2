cmake_minimum_required(VERSION 3.10)
project(TestX2)

set(CMAKE_CXX_STANDARD 17)

set(INCLUDE_DIR ${CMAKE_BINARY_DIR}/../Includes)
include_directories(${INCLUDE_DIR})

add_library(TestX2 library.cpp)

