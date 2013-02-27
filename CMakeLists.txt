project(avgui)
cmake_minimum_required(VERSION 2.6)

find_package(Boost 1.48 REQUIRED system program_options regex)
find_package(Threads)
include_directories(${Boost_INCLUDE_DIRS})
include_directories(include)

add_subdirectory(src)