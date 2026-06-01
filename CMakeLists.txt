cmake_minimum_required(VERSION 3.20)
project(SentinelCV)
set(CMAKE_CXX_STANDARD 20)
add_executable(
    sentinel_server
    apps/sentinel_server/main.cpp
)