This project focuses on designing and implementing a differential drive robot navigation system. The robot is designed using Fusion 360 and converted into the URDF format using a dedicated plugin. The navigation system is then simulated and launched in ROS Noetic, providing a comprehensive platform for testing and refining the robot's autonomous navigation capabilities.

Key Features:

Differential Drive Robot: The project centers around a differential drive robot, a popular and versatile robotic platform known for its maneuverability and simplicity.
Fusion 360 Design: The robot is meticulously designed using Fusion 360, a powerful CAD software that allows for precise modeling and visualization.
URDF Conversion: A custom plugin is utilized to convert the Fusion 360 design into the Unified Robot Description Format (URDF), a widely adopted standard in ROS for robot representation.
ROS Noetic Integration: The URDF model is seamlessly integrated into ROS Noetic, an open-source framework for building robot systems, to enable simulation and navigation capabilities.
Simulated Environment: The robot's navigation system is tested in a simulated environment to ensure proper functioning before real-world deployment.
Differential Drive Control: The robot's differential drive system is implemented and controlled within the ROS Noetic environment, enabling autonomous movement and precise control.
Navigation Algorithms: Various navigation algorithms, such as SLAM (Simultaneous Localization and Mapping) and path planning algorithms, can be implemented and evaluated within the project.

Launch :
1. Install ROS Noetic
2. Clone the Repository
3. Build the Catkin Workspace
4. Launch the Simulation
   cd ~/catkin_ws/
   catkin_make
   source devel/setup.bash
   roslaunch differential_drive_description gazebo.launch
