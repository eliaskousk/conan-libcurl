PROJECT(conanlibcurl)
cmake_minimum_required(VERSION 2.8)
include(conanbuildinfo.cmake)

CONAN_BASIC_SETUP()
add_subdirectory("./curl-7.54.0")
