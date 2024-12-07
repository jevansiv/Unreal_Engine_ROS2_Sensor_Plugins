## Sensor Configuration

This sensor suite is built upon **[rclUE](https://github.com/rapyuta-robotics/rclUE/tree/UE5_devel_humble)** and **[RapyutaSimulationPlugins](https://github.com/rapyuta-robotics/RapyutaSimulationPlugins/tree/devel)** to deliver a versatile and adjustable sensor array, simulating sensors and autonomous systems in **Unreal Engine 5.1** using **ROS2 Humble** on **Ubuntu 22.04**.

### Virtual Sensor Suite
The virtual setup includes the following sensors:  
- **GPS**: Simulated GPS for positioning and navigation.  
- **IMU**: Provides heading and orientation data.  
- **LiDAR**: High-resolution Ouster LiDAR for obstacle detection and environmental mapping.  
- **Depth Camera**: Enables depth perception for object recognition and obstacle avoidance.  
- **RGB Camera**: Captures high-quality visual data for scene analysis.  
- **FLIR Camera**: Simulates thermal imaging for advanced perception in various environments.  
- **Contact Sensors**: Detect physical interaction with objects in the environment.  
- **3D LiDAR**: Simulates full-range 3D mapping capabilities.  
- **2D LiDAR**: Provides planar mapping and obstacle detection.  
- **Ultrasonic Sensors**: Simulate short-range distance measurements.  
- **Radar**: Detects objects using radio waves, ideal for poor visibility conditions.  

### Simulation Reference
Details on integrating these sensors into the ROWMow Sim platform can be found in the referenced work:  
**Mardikes, M., Evans, J., Brown, E., Sprague, N., Wiegman, T., Supe, S., & Shaver, G. (2024). *ROWMow Sim: A Digital-Twin Robotic Simulator for Testing Autonomous Roadside Mowers.* Unpublished manuscript.**

This citation provides a comprehensive overview of the sensor models' design and their integration into the digital-twin robotic testing environment.

### BibTeX Citation
```bibtex
@unpublished{mardikes2024rowmowsim,
  author    = {Mardikes, M. and Evans, J. and Brown, E. and Sprague, N. and Wiegman, T. and Supe, S. and Shaver, G.},
  title     = {ROWMow Sim: A Digital-Twin Robotic Simulator for Testing Autonomous Roadside Mowers},
  year      = {2024},
  note      = {Unpublished manuscript}
}
