cmake_minimum_required(VERSION 3.10)

project(fabula)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_FLAGS "-Wall")

add_executable(${PROJECT_NAME} main.cpp)