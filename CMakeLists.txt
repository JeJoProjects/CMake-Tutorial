cmake_minimum_required(VERSION 3.10)

# set the project
project("Tutorial")

# specify the sources
add_subdirectory (Sources)
set(SOURCES_INCLUDE_DIR  ${CMAKE_CURRENT_SOURCE_DIR}/Sources)
