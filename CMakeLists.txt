project(xp_udf)
cmake_minimum_required(VERSION 3.9)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_STANDARD 11)

include_directories(/usr/include/mysql)

add_library(xp MODULE xp.cpp)
