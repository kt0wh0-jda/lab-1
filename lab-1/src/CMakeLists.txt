cmake_minimum_required(VERSION 3.10)  
project(LAB-1)                    

set(CMAKE_CXX_STANDARD 14)         

include_directories(src)

set(SOURCE_FILES src/main.cpp src/utils.cpp)

add_executable(lab_1 main.cpp) 

