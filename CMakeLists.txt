project(http-server)

cmake_minimum_required(VERSION 2.8)

#SET(CMAKE_C_COMPILER gcc)
#SET(CMAKE_CXX_COMPILER g++)

SET(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3 -g")
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3 -g -std=c++11")

add_definitions(
)

add_subdirectory(src)

