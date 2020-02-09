cmake_minimum_required(VERSION 3.0)

set (CMAKE_BUILD_TYPE Debug)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
add_executable(helloworld main.cpp)

target_link_libraries(helloworld -static-libstdc++ -static-libgcc)