cmake_minimum_required(VERSION 3.21)
project(bpe)

set(CMAKE_CXX_STANDARD 14)

add_executable(compress compress.c)
add_executable(expand expand.c)
