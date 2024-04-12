cmake_minimum_required(VERSION 3.5)

project(XCW CXX)

add_executable(${PROJECT_NAME}
    Joystick.cpp
    Serial.cpp
    Serial.hpp

)