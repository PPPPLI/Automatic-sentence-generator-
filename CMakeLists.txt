cmake_minimum_required(VERSION 3.23)
project(ProjetC C)

set(CMAKE_C_STANDARD 99)
# clion stack
MATH(EXPR stack_size "4*1024*1024")
set(CMAKE_EXE_LINKER_FLAGS "-Wl,--stack,${stack_size}")

add_executable(ProjetC Resource/main.c Resource/importation.c Resource/importation.h Resource/dicArbre.h Resource/dicArbre.c Resource/nodeFind.h Resource/nodeFind.c Resource/toSentence.h Resource/toSentence.c Resource/verbFind.h Resource/verbFind.c Resource/adjFind.h Resource/adjFind.c Resource/dicNettoyer.c Resource/dicNettoyer.h)
