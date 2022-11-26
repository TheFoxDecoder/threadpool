cmake_minimum_required(VERSION 3.16)
project(ThreadPool )

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_BUILD_TYPE Debug)
include_directories(include)


set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize=address ")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O0")

add_subdirectory(include)
add_subdirectory(Test)