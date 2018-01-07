cmake_minimum_required(VERSION 3.8)
project(SimpleBash)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        sh.c)

add_executable(SimpleBash ${SOURCE_FILES})