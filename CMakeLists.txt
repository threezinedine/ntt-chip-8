cmake_minimum_required(VERSION 3.28)
project(Chip8Emulator)

file(
    GLOB
    SOURCES
    src/*.cpp
)

file(
    GLOB
    HEADERS
    inc/chip8/*.h
)

add_executable(
    ${PROJECT_NAME}
    ${SOURCES}
    ${HEADERS}
)