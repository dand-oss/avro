cmake_minimum_required(VERSION 3.2)
project(protobuf CXX)

###############
# ASI default settings
list(APPEND CMAKE_MODULE_PATH "$ENV{ASI}/cmake/Modules")
include(asv_cmake_defaults)
asv_cmake_defaults( )
###############

add_subdirectory(lang/c)
