cmake_minimum_required(VERSION 3.5.1)
project(jsonxx)

set(CMAKE_CXX_STANDARD 14)

add_library(jsonxx STATIC jsonxx.cc)

add_executable(jsonxx_test jsonxx_test.cc)
target_link_libraries(jsonxx_test jsonxx)
