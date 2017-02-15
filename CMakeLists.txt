cmake_minimum_required(VERSION 3.2)
project(avro C)

###############
# ASI default settings
list(APPEND CMAKE_MODULE_PATH "$ENV{ASI}/cmake/Modules")
include(asv_cmake_defaults)
asv_cmake_defaults( )
###############

list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/lang/c/")
add_subdirectory(lang/c)
