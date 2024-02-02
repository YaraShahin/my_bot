## Robot Package Template

contains config files for urdf, other HW descriptions, and simulation launch files. 

# Prequisites

- install ros2 full
- install python3 tools
- install gazebo for ros2
- install xacro

# Commands

`source /opt/ros/foxy/setup.bash`
`source install/setup.bash`
`colcon build --symlink-install`

`ros2 run teleop_twist_keyboard teleop_twist_keyboard`
`ros2 run <your-package-name> launch_sim.launch.py`

# Todos

- set all the harware dimensions in variables in parameters.yaml and then use them in the urdf xacro instead of hardcoded numbers
