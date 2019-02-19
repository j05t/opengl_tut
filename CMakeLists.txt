cmake_minimum_required(VERSION 3.13)
project(opengl)

set(CMAKE_CXX_STANDARD 11)

add_executable(opengl main.cpp glad.c shader_s.h)