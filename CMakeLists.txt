cmake_minimum_required(VERSION 3.25)
project(SR1-Carga_de_Modelos)

set(CMAKE_CXX_STANDARD 17)
set(SDL2_INCLUDE_DIR C:/libs/SDL/include)
set(SDL2_LIB_DIR C:/libs/SDL/lib/x64)

include_directories(${SDL2_INCLUDE_DIR})
link_directories(${SDL2_LIB_DIR})
include_directories("C:/MinGW/include/glm")

add_executable(SR1-Carga_de_Modelos main.cpp)

target_link_libraries(${PROJECT_NAME} SDL2main SDL2)
