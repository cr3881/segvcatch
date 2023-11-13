project(segvcatch)

cmake_minimum_required(VERSION 2.6)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
include_directories(lib)

add_subdirectory(lib)
add_subdirectory(test)


