cmake_minimum_required(VERSION 3.17)
project(Highkick)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(example)
include_directories(src)

add_executable(Highkick
        LICENSE
        README.md)
