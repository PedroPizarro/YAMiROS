cmake_minimum_required(VERSION 3.17.4 FATAL_ERROR)

project(YAMiROS
        VERSION 0.0.1
        DESCRIPTION "Yet Another Minial Real-time Operating System"
        LANGUAGES CXX ASM)

# YAMiROS language version
set(CMAKE_CXX_STANDARD 17)

add_library(${PROJECT_NAME})

target_compile_options(${PROJECT_NAME} PRIVATE -Wall -Wextra -Wfloat-equal 
-Wundef -Wcast-align -Wwrite-strings -Wlogical-op -Wmissing-declarations 
-Wredundant-decls -Wshadow -Woverloaded-virtual -Wunused-variable -Werror)

add_subdirectory(source)