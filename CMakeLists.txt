cmake_minimum_required(VERSION 3.10)

# set the project
project("Tutorial"
    VERSION 1.0
    ${PROJECT_NAME} HOMEPAGE_URL "https://github.com/JeJoProjects/CMake-Tutorial")

# specify the sources
add_subdirectory (Sources)
set(SOURCES_INCLUDE_DIR  ${CMAKE_CURRENT_SOURCE_DIR}/Sources)

target_include_directories(${PROJECT_NAME} PUBLIC
    "${PROJECT_BINARY_DIR}")
