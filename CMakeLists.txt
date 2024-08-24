cmake_minimum_required(VERSION 3.28)
project(BigInt)

set(CMAKE_CXX_STANDARD 20)

add_executable(BigInt main.cpp
        BigInt.cpp
        BigInt.h)
