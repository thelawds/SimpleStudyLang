cmake_minimum_required(VERSION 3.21)
project(SimpleLang VERSION 0.1)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED 20)

# Setting Executables:
add_executable(
	SimpleLang
	src/main.cpp
)

