cmake_minimum_required(VERSION 3.18.0)

project(EMBSYS VERSION 1.0)

find_package(Catch2 REQUIRED)

include (CTest)
include (Catch)

add_subdirectory(FirstExample)

add_subdirectory(Greeting)