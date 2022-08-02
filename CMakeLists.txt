cmake_minimum_required(VERSION 3.0.0)
project(DTW_Project VERSION 0.1.0)

add_executable(DTW_Project dtw_learning/main.cpp)
include_directories(includes)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)