cmake_minimum_required(VERSION 4.1)
project(tide C CXX)

set(CMAKE_C_STANDARD 17)
set(CMAKE_CXX_STANDARD 20)

add_executable(tide sandbox.cpp)