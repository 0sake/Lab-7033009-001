cmake_minimum_required(VERSION 3.15)
project(Lab_7033009_002)

set(CMAKE_CXX_STANDARD 14)

add_executable(Lab_7033009_002 main.cpp Google_Test/test1.cpp)
add_subdirectory(Google_Test)