cmake_minimum_required(VERSION 3.1)
PROJECT ( keygen-decompilation C CXX )

set (CMAKE_CXX_STANDARD 11)

file(GLOB keygen_SRC
    "*.h"
    "*.cpp"
)

add_executable(keygen-decompilation ${keygen_SRC})