# CMakeLists.txt
cmake_minimum_required(VERSION 3.16)

project(eeredis CXX)

# Set C++ STD 17 
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(src)
add_subdirectory(test)
