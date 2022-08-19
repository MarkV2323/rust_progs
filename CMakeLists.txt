cmake_minimum_required(VERSION 3.16)

# specifiy the project is C language only.
project(rustProgs C)


# primary exe
add_executable(helloWorld
        src/helloWorld.c
        )
