cmake_minimum_required(VERSION 3.23.2)
project(stb-cmake VERSION 1.0.0)

add_library(stb-cmake stb_vorbis.c)

target_include_directories(stb-cmake PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})