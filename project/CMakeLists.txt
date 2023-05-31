cmake_minimum_required(VERSION 3.23)
project(project)

set(CMAKE_CXX_STANDARD 23)

set(SOURCES
        src/main.cpp
        src/BasicProgram/BasicProgram.cpp
        )

add_executable(project ${SOURCES})
