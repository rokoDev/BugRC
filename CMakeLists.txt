set(cmake_version 3.18.3)

cmake_minimum_required(VERSION ${cmake_version})

set(ProjectName "BugRC")

project(${ProjectName}
		VERSION 0.1.0
		LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

set(SOURCES ${CMAKE_SOURCE_DIR}/src/main.cpp)

# Create executable
add_executable("example" ${SOURCES})