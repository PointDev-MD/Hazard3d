cmake_minimum_required(VERSION 3.10)
project(Hazard3d VERSION 0.2)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

find_package(OpenGL REQUIRED)
find_package(glfw3 REQUIRED)
find_package(GLEW REQUIRED)
find_package(glm REQUIRED)

add_executable(Hazard3d src/main.cpp)

target_link_libraries(Hazard3d OpenGL::GL glfw GLEW::GLEW glm::glm)