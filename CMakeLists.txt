cmake_minimum_required(VERSION 3.2.3)

project(Cloud-Rendering  VERSION 1.0)


# specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_subdirectory(src)


#target_link_libraries(cloudray ${log-lib} )