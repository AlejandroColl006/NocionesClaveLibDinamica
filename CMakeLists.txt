cmake_minimum_required(VERSION 3.29)
project(NocionesClaveLibDinamica)

set(CMAKE_CXX_STANDARD 20)

add_library(NocionesClaveLibDinamica SHARED src/funciones.cpp)

target_compile_definitions(NocionesClaveLibDinamica PRIVATE NOCIONESCLAVE_LIB_EXPORT)
