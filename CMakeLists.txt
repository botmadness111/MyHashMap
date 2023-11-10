cmake_minimum_required(VERSION 3.26)
project(HashMap)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(HashMap
        Hash.cpp
        Hash.h
        Hash2.cpp
        Hash2.h
        HashTable.cpp
        HashTable.h
        HashTableBin.cpp
        HashTableBin.h)
