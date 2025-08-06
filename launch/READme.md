This folder contains all the **ROS 2 launch files** responsible for starting various components of the `my_bot` robot.

### Launch Files:

- **`launch_robot.launch.py`**  
   Launches the robot with its **URDF** and **ROS 2 Control** interfaces (for real hardware or basic simulation).

- **`launch_sim.launch.py`**  
   Starts the **full simulation** environment including **Gazebo** and the robot description.

- **`rsp.launch.py`**  
   Launches the **Robot State Publisher** — crucial for **TF tree broadcasting** and **visualization in RViz**.

- **`rplidar.launch.py`**  
   Initializes the **RPLiDAR node** to stream laser scan data for mapping or navigation.

- **`online_async_launch.py`**  
   Launches **SLAM Toolbox** in **asynchronous mode** to enable **real-time mapping** of the environment.
