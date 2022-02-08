cmake_minimum_required(VERSION 3.21)
project(CppProgrammingPathToDataStructure)

set(CMAKE_CXX_STANDARD 20)
set(SOURCE_FILES main.cpp test_class.cpp test_class.h)
add_executable(CppProgrammingPathToDataStructure ${SOURCE_FILES} test_class.cpp test_class.h)