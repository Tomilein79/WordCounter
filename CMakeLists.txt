cmake_minimum_required(VERSION 3.13)
project(WordCounter)

set(CMAKE_CXX_STANDARD 14)

include_directories(WordCounter)

add_executable(WordCounter
        WordCounter/WordCounter.cpp)
