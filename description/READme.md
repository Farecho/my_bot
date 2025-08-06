This directory contains the URDF and Xacro files defining the physical and simulation characteristics of the `my_bot` robot.
These files are used for visualization in RViz, simulation in Gazebo, and integration with ROS 2 Control and SLAM.

## File Overview

- **`gazebo_control.xacro`**  
  Adds Gazebo-specific plugins and configurations for simulating control interfaces (e.g., joint controllers, transmission).

- **`inertial_macros.xacro`**  
  Defines macros for setting inertial properties (mass, inertia matrix) of robot components. Helps reduce redundancy in the robot description.

- **`lidar.xacro`**  
  Contains the LIDAR sensor definition. Essential for SLAM and map generation.

- **`robot.urdf.xacro`**  
  The top-level Xacro file that brings together all components (`robot_core`, sensors, control, etc.) into a complete robot description.

- **`robot_core.xacro`**  
  Defines the base structure and links of the robot (e.g., chassis, wheels). Core to both simulation and real robot setups.

- **`ros2_control.xacro`**  
  Provides the necessary elements to interface the robot with ROS 2 Control. Used for hardware abstraction and control.


This package is meant to:

- Enable robot simulation in Gazebo.
- Provide a structured URDF for visualization in RViz.
- Support SLAM and mapping functionalities.
- Integrate with ROS 2 Control for motion and joint control.

