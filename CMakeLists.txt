cmake_minimum_required(VERSION 3.16A)

project(chip8 VERSION 1.0
        DESCRIPTION "Chip8 emulator / interpreter"
        LANGUAGES CXX)

add_subdirectory(src)
add_subdirectory(tests)

