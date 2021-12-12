cmake_minimum_required (VERSION 3.2)
project (stb-image)

add_library(
        stb-image
        stb_image.c
)

target_include_directories(
        stb-image
        PUBLIC
        .
)
