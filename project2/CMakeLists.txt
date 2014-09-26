project(LeniwyKlasyfikator)
cmake_minimum_required(VERSION 2.8)

file(GLOB SOURCE_LIST *.cpp)
file(GLOB HEADER_LIST *.h)

add_executable(${PROJECT_NAME} ${SOURCE_LIST} ${HEADER_LIST})
