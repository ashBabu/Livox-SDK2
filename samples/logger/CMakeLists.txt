cmake_minimum_required(VERSION 3.6)

set(DEMO_NAME logger)
add_executable(${DEMO_NAME} main.cpp)

target_link_libraries(${DEMO_NAME}
        PUBLIC
        livox_lidar_sdk_static)

