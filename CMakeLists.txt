cmake_minimum_required(VERSION 3.10)
project(rapidjson)

add_library(rapidjson INTERFACE)
target_include_directories(rapidjson SYSTEM INTERFACE include)
target_compile_definitions(rapidjson INTERFACE RAPIDJSON_HAS_STDSTRING=1)
