cmake_minimum_required(VERSION 3.15)
project(helloWorld)

set(CMAKE_CXX_STANDARD 20)

add_executable(helloWorld main.cpp)
install(TARGETS helloWorld DESTINATION bin)

