cmake_minimum_required(VERSION 3.0)

project(ci_demo)

file(GLOB DEMO_SOURCE *.cpp *.cc)
add_executable(ci_demo ${DEMO_SOURCE})
