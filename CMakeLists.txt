cmake_minimum_required(VERSION 3.12)

set(CMAKE_C_COMPILER "/usr/bin/clang")

project(garbage-collector)

FILE(GLOB all_SRCS *.c)
add_executable(garbage-collector ${all_SRCS})