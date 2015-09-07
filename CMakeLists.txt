cmake_minimum_required(VERSION 3.0)
project(EMACLlib)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c11")

set(SOURCE_FILES src/main.c)
add_executable(EMACLlib ${SOURCE_FILES})