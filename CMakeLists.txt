cmake_minimum_required(VERSION 3.17)
project(artronics_firmware)

enable_language(CXX C ASM)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_C_EXTENSIONS OFF)
add_subdirectory(tests)

add_executable(artronics_firmware src/main.cpp)