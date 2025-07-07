# ros2_joystick_config
ROS2 joystick configurations for a XEOX Gamepad SL-6556-BK

This is intended for use with the ROS2 teleop-twist-joy package.
(https://github.com/ros2/teleop_twist_joy)

Configurations Available:
|Configuration|Description|
|-------------|-----------|
|single_xeox.config.yaml|Left axes controls fwd/bwd and rotates left/right|
|dual_xeox.config.yaml|Left axes controls fwd/bwd, right axes rotates left/right|
|holonomic_xeox.config.yaml|Left axes controls fwd/bwd and holonomic left/right, right axes rotates left/right|

# Example use:

```ros2 launch teleop_twist_joy teleop-launch.py config_filepath:=./src/ros2_joystick_config/joystick_config/config/dual_xeox.config.yaml```
