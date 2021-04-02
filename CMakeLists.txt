cmake_minimum_required(VERSION 3.17)
project(antSim)

set(CMAKE_CXX_STANDARD 20)

add_executable(antSim src/main.cpp src/gui.cpp src/gui.hpp)