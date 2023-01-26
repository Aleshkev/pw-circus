cmake_minimum_required(VERSION 3.16)
project(pw_circus)

set(CMAKE_CXX_STANDARD 20)

include_directories(.)

add_executable(pw_circus
        demo.cpp
        machine.hpp
        system.cpp
        system.hpp)
