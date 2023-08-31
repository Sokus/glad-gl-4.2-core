cmake_minimum_required(VERSION 3.5)
project(glad)

add_library(glad INTERFACE)
target_include_directories(glad INTERFACE include)