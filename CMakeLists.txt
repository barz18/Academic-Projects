cmake_minimum_required(VERSION 3.28.3)
project(wet)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(wet
        Matrix.cpp
        Matrix.h
        tests.cpp
        Utilities.cpp
        Utilities.h
        MataMvidia.cpp)
