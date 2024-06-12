cmake_minimum_required (VERSION 3.30)

project("App" 
		VERSION 0.0.1 
		LANGUAGES CXX)

add_executable(App "main.cpp" "main.h")
add_executable(App_Win32 "main.cpp" "main.h")

set_property(TARGET App PROPERTY CXX_STANDARD 20)
