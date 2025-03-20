`colcon build --symlink-install`
`source install/setup.bash`
`ros2 launch my_robot_bringup launch_sim.launch.py world:=./src/my_robot_bringup/worlds/obstacles.world`
`ros2 launch my_robot_bringup launch_sim.launch.py world:=./src/my_robot_bringup/worlds/empty.world`