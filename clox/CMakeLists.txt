cmake_minimum_required(VERSION 4.1)

#waiting for CMAKE 4.3 to remove this
if(CMAKE_VERSION VERSION_EQUAL "4.1.2")
  set(CMAKE_EXPERIMENTAL_CXX_IMPORT_STD "d0edc3af-4c50-42ea-a356-e2862fe7a444")
endif()

project(clox CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_MODULE_STD 1)

add_executable(clox src/main.cpp)
