# Space Navigator – SLAM-Based Autonomous Navigation Robot

This repository contains the implementation of the **Space Navigator** project, an autonomous robot navigation system using **ROS2**, **Navigation2 stack**, and **SLAM**. The goal was to integrate hardware control and autonomous navigation capabilities into a robot capable of mapping and localizing itself in an unknown environment.

---

## 📌 Project Overview

The **Space Navigator** was developed as part of an academic project under the guidance of [Dr. Shayok Mukhopadhyay](mailto:smukhopadhyay@unh.newhaven.edu) at the University of New Haven.

### 🧠 Objectives
- Hardware interfacing using Arduino (motors, ultrasonic sensors, IMU)
- Implement PID control for maintaining direction/distance
- Use **SLAM** for real-time map generation
- Navigate autonomously using the **Nav2 stack**
- Simulate robot behavior in a custom **Gazebo world**

---

## 🛠️ Tech Stack

| Component         | Technology Used               |
|------------------|-------------------------------|
| Middleware       | ROS2 (Humble Hawksbill)       |
| Mapping          | SLAM Toolbox (`slam_toolbox`) |
| Simulation       | Gazebo                        |
| Visualization    | RViz2                         |
| Robot Control    | Arduino + Serial              |
| Programming Lang | C++, Python                   |

---

## 🗺️ Features

✅ Real-time SLAM map generation  
✅ Custom Gazebo world (`mynewhouse`)  
✅ RViz integration for robot pose and map visualization  
✅ PID control with IMU for smooth movement  
✅ ROS2 TF setup: `map → odom → base_link → base_scan`  
✅ Save and load maps for persistent navigation  
✅ Launch files and URDF for easy simulation

---


