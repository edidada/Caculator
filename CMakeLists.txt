cmake_minimum_required(VERSION 3.10)

project(Caculator VERSION 1.0 LANGUAGES C)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_executable(caculator caculator.c)
