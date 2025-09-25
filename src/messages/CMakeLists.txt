add_library(messaggi base_sensor_message.cpp odometry_message.cpp pose_message.cpp)
target_include_directories(messaggi PRIVATE ${CMAKE_SOURCE_DIR}/src)
target_include_directories(messaggi PRIVATE ${EIGEN3_INCLUDE_DIR})