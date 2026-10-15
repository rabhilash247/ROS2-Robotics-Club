## 📂 Repository Contents

The repository is organized to make ROS 2 concepts, simulation setup, and practical robotics exercises easier to explore.

```text
ROS2/
├── README.md
├── setup_turtlebot3_sim.sh
├── check_simulation.sh
└── Learning Topics
    ├── ROS 2 Fundamentals
    ├── Python ROS 2 Programming
    ├── TurtleBot3 Simulation
    ├── Gazebo and RViz2
    ├── Robot Control and Teleoperation
    ├── LiDAR, Odometry and TF
    ├── SLAM Mapping
    ├── Map Saving
    ├── Navigation2 (Nav2)
    └── Troubleshooting
```

### Contents Overview

| File / Topic | Description |
|---|---|
| `README.md` | Main documentation, setup instructions, commands, and learning roadmap. |
| `setup_turtlebot3_sim.sh` | Helper script for installing and configuring the TurtleBot3 simulation environment. |
| `check_simulation.sh` | Helper script for checking simulation status, topics, sensor data, and robot movement. |
| ROS 2 Fundamentals | Introduction to nodes, topics, services, actions, and parameters. |
| Python ROS 2 Programming | Creating nodes, publishers, subscribers, and callbacks with `rclpy`. |
| TurtleBot3 and Gazebo | Launching and controlling a simulated mobile robot. |
| RViz2 Visualization | Visualizing robot models, LiDAR scans, coordinate frames, and maps. |
| SLAM Mapping | Building and saving maps using SLAM Toolbox. |
| Navigation2 (Nav2) | Exploring map-based autonomous navigation. |
| Troubleshooting | Common setup, simulation, visualization, and navigation issues. |

**Note:** The tree above describes the intended organization. The shell scripts and separate learning-topic folders should be added to the repository if they do not already exist. The learning topics may currently be documented within `README.md` rather than stored as separate files.
