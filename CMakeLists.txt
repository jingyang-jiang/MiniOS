cmake_minimum_required(VERSION 3.15)
project(Comp310_A3 C)

set(CMAKE_C_STANDARD 11)

add_executable(Comp310_A3 cpu.c cpu.h interpreter.c interpreter.h kernel.c kernel.h pcb.c pcb.h ram.c ram.h shell.c shell.h shellmemory.c shellmemory.h memorymanager.c memorymanager.h)