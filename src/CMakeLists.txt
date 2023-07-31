cmake_minimum_required (VERSION 3.8)

add_executable (ci "main.cpp")

set_target_properties(ci PROPERTIES VS_DEBUGGER_WORKING_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR})
