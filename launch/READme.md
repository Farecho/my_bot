This folder contains all the ROS 2 launch files used for bringing up various functionalities of the my_bot robot.
Each launch file serves a specific purpose, from simulation to mapping.

launch_robot.launch.py
Launches the robot with URDF and ROS 2 Control (real hardware or minimal sim).

launch_sim.launch.py
Starts the full simulation environment including Gazebo and robot description.

rsp.launch.py
Launches the Robot State Publisher, useful for visualization in RViz.

rplidar.launch.py
Brings up the RPLiDAR node for laser data streaming.

online_async_launch.py
Launches SLAM Toolbox in asynchronous mode for real-time map generation.


