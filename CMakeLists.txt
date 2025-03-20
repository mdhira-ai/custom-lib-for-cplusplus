cmake_minimum_required(VERSION 3.10.0)
project(test1 VERSION 0.1.0 LANGUAGES C CXX)

add_executable(test1 main.cpp lib/mylib.cpp)

target_include_directories(test1 PUBLIC lib)

