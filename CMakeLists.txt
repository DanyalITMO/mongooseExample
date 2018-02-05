cmake_minimum_required(VERSION 3.9)
project(mongoose_example)

set(CMAKE_CXX_STANDARD 17)

set(SOURCE_FILES main.cpp mongoose.c)
add_executable(mongoose_example ${SOURCE_FILES})