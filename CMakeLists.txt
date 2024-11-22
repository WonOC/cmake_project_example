cmake_minimum_required(VERSION 3.14)

set(PROJECT_NAME cmake_project_example)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_BUILD_TYPE Debug)

project(${PROJECT_NAME})
add_executable(${PROJECT_NAME} src/main.cpp)