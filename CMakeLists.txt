cmake_minimum_required(VERSION 3.22)

project(sfml-imgui)

add_executable(${PROJECT_NAME})

add_subdirectory(lib)
add_subdirectory(include)
add_subdirectory(src)