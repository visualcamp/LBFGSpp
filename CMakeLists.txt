cmake_minimum_required(VERSION 3.5)

project(lbfgs LANGUAGES CXX)

add_library(lbfgs INTERFACE)

target_include_directories(lbfgs INTERFACE include)
