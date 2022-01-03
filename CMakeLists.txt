cmake_minimum_required(VERSION 3.17.4 FATAL_ERROR)
include(extern/pico-sdk/pico_sdk_init.cmake)

project(YAMiROS
        VERSION 0.0.1
        DESCRIPTION "Yet Another Minial Real-time Operating System"
        LANGUAGES CXX C)

# Pico SDK initialization
# Uses C11 and C++11
pico_sdk_init() 

# Our language version
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_C_STANDARD 11)