cmake_minimum_required(VERSION 4.0)
project(Ulla_Engine)

set(CMAKE_CXX_STANDARD 26)

# Vulkan
find_package(Vulkan REQUIRED)

# GLFW (installed via Homebrew: brew install glfw)
find_package(glfw3 3.3 REQUIRED)

# GLM (installed via Homebrew: brew install glm)
find_package(glm REQUIRED)

add_executable(Ulla_Engine main.cpp)
