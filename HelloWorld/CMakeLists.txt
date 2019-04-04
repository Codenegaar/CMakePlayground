cmake_minimum_required(VERSION 2.8)

project(HelloWorld)

set(EXECUTABLE_OUTPUT_PATH ${CMAKE_BINARY_DIR})
set(LIBRARY_OUTPUT_PATH ${CMAKE_BINARY_DIR})

add_executable(${PROJECT_NAME} ${CMAKE_SOURCE_DIR}/main.cpp)
