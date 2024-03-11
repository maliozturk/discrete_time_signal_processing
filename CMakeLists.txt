cmake_minimum_required(VERSION 3.26)
project(discrete_time_signal_processing)

set(CMAKE_CXX_STANDARD 17)

add_executable(discrete_time_signal_processing main.cpp
        src/first.cpp
        include/first.h)

target_include_directories(discrete_time_signal_processing PUBLIC include/)