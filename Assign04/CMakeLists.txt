cmake_minimum_required(VERSION 3.13)
project(Assign04Workspace)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Assign04Workspace
        Makefile
        sequence.h
        sequence.template
        sequenceTest.cpp)
