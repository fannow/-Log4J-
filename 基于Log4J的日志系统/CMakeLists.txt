#指定cmake的最低版本
CMAKE_MINIMUM_REQUIRED(VERSION 3.9)
#添加当前目录存放源文件的目录
add_definitions(-std=c++11)
add_definitions(-lyaml-cpp)
aDD_SUBDIRECTORY(./code)
ADD_SUBDIRECTORY(./main)
