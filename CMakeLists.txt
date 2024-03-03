cmake_minimum_required (VERSION 3.20)

project (BuggyTertis)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_COMPLIER "clang")
set(CMAKE_CXX_FLAGS "-Werror")


include_directories(include/)

add_executable(Tertis src/main.cpp)