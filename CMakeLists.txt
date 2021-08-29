cmake_minimum_required( VERSION 3.10)

PROJECT(my_lib)

add_library(my_lib
    src/my_lib.cpp
)

target_include_directories( my_lib
    PUBLIC
    inc
)   