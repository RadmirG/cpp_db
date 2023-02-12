cmake_minimum_required(VERSION 3.24)
project(cpp_mysql)

set(CMAKE_CXX_STANDARD 17)

# sqlite connector sources
set(FULL_PATH_TO_SQLITE "C:\\sqlite")
# sqlite includes
include_directories(${FULL_PATH_TO_SQLITE})
# sqlite libs
#link_directories(${FULL_PATH_TO_SQLITE})

add_executable(cpp_mysql main.cpp)
