cmake_minimum_required(VERSION 3.29.6)

project(Robot_algorithm LANGUAGES CXX C)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(Robot_algorithm src/main.cpp
        src/a.cpp
        include/a.h)