cmake_minimum_required(VERSION 3.29)
project(SYSC4001_A2_P3)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -static-libstdc++ -static-libgcc")

include_directories(.)

add_executable(SYSC4001_A2_P3
    interrupts.cpp
    interrupts.hpp)
