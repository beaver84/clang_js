cmake_minimum_required(VERSION 3.23)
project(clang_js C)

set(CMAKE_C_STANDARD 99)

add_executable(clang_js main.c 7_2.c 7_3.c 7_5.c)
