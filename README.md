## Robot Package Template

# rebuild ws after adding files
colcon build --symlink-install

# source installation
source install/setup.bash

# launch the simulator
ros2 launch my_bot launch_sim.launch.py

# twist keyboard
ros2 run teleop_twist_keyboard teleop_twist_keyboard