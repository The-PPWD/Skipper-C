cmake_minimum_required(VERSION 3.16.3)

project(skipper VERSION 1.0.0 LANGUAGES C)

add_subdirectory(src skipperc)
add_subdirectory(test skipperc/test)
