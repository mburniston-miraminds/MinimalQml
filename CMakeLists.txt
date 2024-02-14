cmake_minimum_required(VERSION 2.8)

# 3rd party tools
find_package(Qt5 COMPONENTS Widgets Qml Quick REQUIRED)

message(STATUS "Qt5_DIR: ${Qt5_DIR}")
message(STATUS "Qt5Widgets_INCLUDE_DIRS: ${Qt5Widgets_INCLUDE_DIRS}")

# Directory with the source code
add_subdirectory(src)


