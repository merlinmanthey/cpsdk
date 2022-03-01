cmake_minimum_required(VERSION 2.8.9)
project (hello)
add_executable(hello testapp.cpp)



install(TARGETS hello)



enable_testing()
add_test(NAME test1 COMMAND hello)
