cmake_minimum_required(VERSION 3.0.0)
project(teleop_twist_ds4)

# find_package(catkin REQUIRED COMPONENTS message_generation std_msgs)

catkin_package()

install(
  DIRECTORY
    launch/
  DESTINATION
    ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
)

install(
  DIRECTORY
    config/
  DESTINATION
    ${CATKIN_PACKAGE_SHARE_DESTINATION}/config
)
