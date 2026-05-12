cmake_minimum_required(VERSION 3.10)

project(formatter_lib)

set(CMAKE_CXX_STANDARD 11)

add_library(formatter_lib STATIC formatter.cpp)
