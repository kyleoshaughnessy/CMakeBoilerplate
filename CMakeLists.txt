cmake_minimum_required(VERSION 3.6)
project(CMakeBoilerplate)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES
    inc/funcs.h
    src/funcs.cpp
    src/main.cpp)

include_directories(inc)

add_executable(CMakeBoilerplate ${SOURCE_FILES})
