# ROS - Teleop Twist with DualShock 4

## Build

    sudo apt install joystick ros-$ROS_DISTRO-joy ros-$ROS_DISTRO-teleop-twist-joy 
    cd ~/catkin_ws/src 
    git clone https://github.com/ksvbka/teleop_twist_ds4.git 
    cd ~/catkin_ws && catkin_make

## Run
    cd ~/catkin_ws/src 
    roslaunch teleop_twist_ds4 teleop_ds4.launch

Command to view output

    rostopic echo /cmd_vel
