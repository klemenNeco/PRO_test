cmake_minimum_required(VERSION 3.0.0)
project(PRO_test VERSION 0.1.0 LANGUAGES C CXX)
set(SOURCE_DIR "C:/Users/neman/OneDrive/Documents/FERI/RG/PRO_test/CMakeLists.txt")

include(CTest)
enable_testing()

add_executable(PRO_test main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
