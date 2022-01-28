cmake_minimum_required(VERSION 3.17.4 FATAL_ERROR)

project(YAMiROS
        VERSION 0.0.1
        DESCRIPTION "Yet Another Minial Real-time Operating System"
        LANGUAGES CXX C ASM)

# YAMiROS language version
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_C_STANDARD 11)

add_library(${PROJECT_NAME})