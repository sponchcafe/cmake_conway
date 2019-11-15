cmake_minimum_required(VERSION 3.0.0)
project(conway VERSION 0.1.0)

include(CTest)
enable_testing()

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(conway)
add_subdirectory(test)
