cmake_minimum_required(VERSION 3.0)
project(MultiServer)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)
include_directories(src)
add_subdirectory(src)
