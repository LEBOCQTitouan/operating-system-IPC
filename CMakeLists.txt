cmake_minimum_required(VERSION 3.25)
project(operating_system_IPC C)

set(CMAKE_C_STANDARD 11)

add_executable(operating_system_IPC main.c supervisor/supervisor.c supervisor/supervisor.h)
