cmake_minimum_required(VERSION 2.8.9)
project(qtpanel)
set(CMAKE_MODULE_PATH ${CMAKE_SOURCE_DIR}/cmake)
set(CMAKE_INCLUDE_CURRENT_DIR ON)
find_package(XCB REQUIRED)
find_package(Qt5Widgets REQUIRED)

add_subdirectory(src)

