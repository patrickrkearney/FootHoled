cmake_minimum_required(VERSION 3.16)

# FootHoled H1 - ESP32-S3
set(IDF_TARGET "esp32s3")

# Include our application source directory
set(EXTRA_COMPONENT_DIRS "${CMAKE_CURRENT_LIST_DIR}/src")

include($ENV{IDF_PATH}/tools/cmake/project.cmake)

project(FootHoled)