cmake_minimum_required(VERSION 3.10)

project(SimpleCMakeProject)

# 设置编译标准
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# 添加可执行文件
add_executable(SimpleCMakeProject main.cpp)
