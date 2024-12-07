## Sensor Configuration

The ROWMow Sim project integrates an advanced sensor suite designed for roadside mowing tasks. The setup enables precise navigation and obstacle avoidance through a combination of sensors and custom ROS2 nodes. These configurations are tailored for virtual and real-world applications, with emphasis on replicating real-world environmental conditions in the simulation.

### Virtual Sensor Suite
The virtual setup includes:
- **GPS**: Simulated GPS for positioning and navigation.
- **IMU**: Simulated IMU data for heading and orientation.
- **LiDAR**: High-resolution Ouster LiDAR simulation for obstacle detection and environmental mapping.
- **Stereo Camera (OAK-D)**: Provides depth perception and object recognition capabilities for obstacle avoidance.

### Real-World Sensor Suite
The real-world setup mirrors the simulation with physical equivalents:
- **High-precision GPS (e.g., RTK GPS)** for accurate positioning.
- **IMU (Inertial Measurement Unit)** for reliable heading estimation.
- **Ouster LiDAR** for 3D environmental perception.
- **OAK-D Stereo Camera** for enhanced depth sensing and obstacle recognition.

### Configuration Highlights
- **Sensor Fusion**: Data from GPS, IMU, LiDAR, and cameras are fused for robust navigation and obstacle detection.
- **Noise Modeling**: The simulation includes configurable noise levels for each sensor to mimic real-world conditions.
- **Adjustable Sampling Rates**: Sampling rates for each sensor can be modified to match specific platform requirements.

### Simulation Reference
The configurations and methodologies for integrating these sensors into the ROWMow Sim platform are detailed in the paper:  
**Mardikes, M., Evans, J., Brown, E., Sprague, N., Wiegman, T., Supe, S., & Shaver, G. (2024). *ROWMow Sim: A Digital-Twin Robotic Simulator for Testing Autonomous Roadside Mowers.* Unpublished manuscript.**

This citation provides in-depth insights into the design and implementation of the sensor models and their integration into the digital-twin environment.

---
