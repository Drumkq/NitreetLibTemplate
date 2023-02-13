cmake_minimum_required(VERSION 3.23)
project(NitreetLibTemplate)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(googletest)

add_library(${PROJECT_NAME} src/MyClass.hpp src/MyClass.cpp)
