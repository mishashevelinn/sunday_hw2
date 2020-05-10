cmake_minimum_required(VERSION 3.16)
project(sunday_hw C)

set(CMAKE_C_STANDARD 99)

add_executable(sunday_hw main.c League.c League.h Match.c Match.h sort-league.c sort-league.h Team.c Team.h)