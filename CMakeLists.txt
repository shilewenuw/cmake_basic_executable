cmake_minimum_required(VERSION 2.8)
project(app_project)
add_executable(myapp main.cc)
install(TARGETS myapp DESTINATION bin)

