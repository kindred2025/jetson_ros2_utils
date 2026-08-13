# jetson_ros2_utils
A utility library for Jetson + ROS2 Humble UAV development, including CPU affinity management, serial communication wrapper, thread-safe message queue, systemd service templates and performance statistic tools for PX4 drone onboard deployment.

Jetson + ROS2 Humble onboard utility toolkit for PX4 UAV.

## Features
- CPU core affinity & process resource isolation scripts
- C++ / Python serial communication wrapper for PX4 UART
- Thread-safe message queue template for ROS2
- Inference latency statistics helper
- Systemd service template for drone perception node
- Jetson power management & remote deployment scripts

## Platform
- Hardware: Jetson Orin NX / Xavier NX
- OS: L4T + Ubuntu 22.04
- ROS: ROS2 Humble
- Flight Controller: PX4 Autopilot

## Usage
See docs folder for deployment tutorial.
