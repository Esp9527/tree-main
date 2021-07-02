cmake_minimum_required(VERSION 3.0)

add_executable(client main.cpp)

target_link_libraries(client net)