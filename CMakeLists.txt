cmake_minimum_required(VERSION 4.0)
project(SentraBin_OS C)

set(CMAKE_C_STANDARD 11)

add_executable(SentraBin_OS
        main.c)
set(CMAKE_EXE_LINKER_FLAGS "-mconsole")
