cmake_minimum_required(VERSION 2.8)
project(test-json)

message(STATUS "CMAKE_VERSION: ${CMAKE_VERSION}")

if(NOT "${CMAKE_CXX_STANDARD}")
  set(CMAKE_CXX_STANDARD 14)
endif()
set(CMAKE_CXX_STANDARD_REQUIRED ON)
message(STATUS "CMAKE_CXX_STANDARD: ${CMAKE_CXX_STANDARD}")

add_executable(${PROJECT_NAME} main.cpp)
