cmake_minimum_required(VERSION 3.1)
project(HelloWorld)

add_executable(helloworld helloworld.c)

install(TARGETS helloworld DESTINATION ${CMAKE_INSTALL_BINDIR})