# Set the minimum version of CMake required
cmake_minimum_required(VERSION 3.23)

# Define the project
project(
	CityBuilder
	VERSION 1.0
	DESCRIPTION "SDL3 version of an SFML tutorial by the same name"
	LANGUAGES CXX
)

# Set the C++ standard to C++20
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)