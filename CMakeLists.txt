cmake_minimum_required(VERSION 3.25)
project(Search)
set(CMAKE_CXX_STANDARD 20)

include_directories(include)
file(GLOB SOURCES "./src/*.cpp")
add_executable(Search ${SOURCES})
