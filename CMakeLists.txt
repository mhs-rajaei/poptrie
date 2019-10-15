cmake_minimum_required(VERSION 3.14)
project(poptrie_master C)

set(CMAKE_C_STANDARD 11)
#set(CMAKE_CXX_STANDARD 11)

include_directories(.)

add_executable(poptrie_master
        tests/basic.c
        tests/basic6.c
        buddy.c
        buddy.h
        poptrie.c
        poptrie.h
        poptrie4.c
        poptrie6.c
        poptrie_private.h)
