cmake_minimum_required(VERSION 3.12)
project(jx C)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_executable(parser src/parser.c)

