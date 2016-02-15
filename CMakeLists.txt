cmake_minimum_required(VERSION 3.3)
project(cpp_lessons_1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(cpp_lessons_1 ${SOURCE_FILES})