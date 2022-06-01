cmake_minimum_required(VERSION 3.22)
project(comp C)

set(CMAKE_C_STANDARD 99)

add_executable(comp main.c common.h chunk.h chunk.c memory.h memory.c debug.c debug.h value.c value.h vm.h vm.c compiler.c compiler.h scanner.c scanner.h)
