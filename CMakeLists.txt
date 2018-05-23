cmake_minimum_required(VERSION 3.8.11)

project(h264bsd)

set(TOPDIR ${CMAKE_CURRENT_SOURCE_DIR})

add_compile_options(-std=c99 -Wno-implicit-function-declaration)

add_subdirectory(src)
add_subdirectory(posix)
