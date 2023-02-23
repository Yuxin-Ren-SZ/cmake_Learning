

project(cmake_Learning)

set(CMAKE_CXX_STANDARD)


# Add tasks subprojects
include(cmake/utils.cmake)
add_subprojects(${CMAKE_SOURCE_DIR})