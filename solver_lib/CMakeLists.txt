cmake_minimum_required(VERSION 3.10)

project(solver_lib)

set(CMAKE_CXX_STANDARD 11)

add_library(solver_lib STATIC solver.cpp)
