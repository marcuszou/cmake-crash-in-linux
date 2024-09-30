cmake_minimum_required(VERSION 3.28)
project(myproject)

find_package(fmt)

set(CMAKE_CXX_STANDARD		 20)
set(CMAKE_CXX_STANDARD_REQUIRED	YES)
set(CMAKE_CXX_EXTENSIONS	OFF)

add_executable(${PROJECT_NAME} main.cpp)

target_link_libraries(${PROJECT_NAME} mylib fmt::fmt)

add_subdirectory(lib)
