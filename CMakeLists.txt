# Benjamin Michael Taylor (bentaylorhk)
# 2023

cmake_minimum_required(VERSION 3.20)

project(
        boilerplate
        VERSION 1.0
        DESCRIPTION "Boilerplate code for CMake projects"
)

set(CMAKE_CXX_STANDARD 20)

include(cmake/targets.cmake)

add_subdirectory(src)