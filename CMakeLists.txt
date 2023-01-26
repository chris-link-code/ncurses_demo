cmake_minimum_required(VERSION 3.24)
project(bookManage)

set(CMAKE_C_STANDARD 17)
set(CMAKE_C_FLAGS "-std=c17 -lncursesw -lpthread")

set(SRC_LIST src/bookManage.c src/file.c src/menu.c src/win.c src/log.c)
add_executable(bookManage ${SRC_LIST})