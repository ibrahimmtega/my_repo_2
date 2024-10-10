cmake_minimum_required(VERSION 3.16)

project(my_repo_2 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(my_repo_2_lib STATIC
  main.cpp
  dummy.h
  dummy.cpp
)
