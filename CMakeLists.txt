cmake_minimum_required(VERSION 3.12)
project(glad_gl_33_core)

add_library(${PROJECT_NAME} src/gl.c include/glad/gl.h include/KHR/khrplatform.h)
target_include_directories(${PROJECT_NAME} PUBLIC include)
