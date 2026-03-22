cmake_minimum_required(VERSION 3.15)
project(snake LANGUAGES C CXX)

set(CMAKE_C_STANDARD 11)
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(snake src/main.cpp)
target_compile_options(snake PRIVATE -Wall -Wextra -Wpedantic)
