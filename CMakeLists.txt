cmake_minimum_required(VERSION 2.8)
project(Minesweeping C)

set(CMAKE_C_STANDARD 99)

add_executable(Minesweeping main.c src/game.h src/game.c)