add_library(solver_lib STATIC solver.cpp)

cmake_minimum_required(VERSION 3.8)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

target_include_directories(solver_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})


