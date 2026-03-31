# 🚗 ROS Robo – Test Package (Custom Robotics Stack)

This repository contains a custom ROS 2 package developed as part of a personal robotics project, integrating hardware control, simulation, and system-level testing. It serves as a unified workspace for developing and validating a mobile robot platform with real-world deployment in mind.

---

## 📌 Overview

The `test` package is a custom-built ROS 2 package designed to bridge simulation and real hardware for a mobile robotic system. It includes:

- Hardware interfaces for microcontrollers (ESP32 / Arduino)
- Simulation setup for testing in Gazebo
- Core ROS 2 nodes for robot control and communication

The project emphasizes **end-to-end robotics development**, covering perception, control, and deployment pipelines.

---

## ⚙️ Tech Stack

- **Framework:** ROS 2  
- **Simulation:** Gazebo  
- **Visualization:** RViz 2  
- **Hardware:** ESP32, Arduino  
- **Programming:** Python (rclpy), Embedded C (Arduino)  
- **Communication:** Serial / microcontroller interfaces  
- **Version Control:** Git  

---

## 🧠 Key Features

### 🔌 Custom Hardware Interface
- Communication between ROS 2 and ESP32/Arduino-based robot  
- Real-time motor and actuator control  

### 🤖 Robot Control Nodes
- Custom ROS 2 nodes for movement and system behavior  
- Publisher–Subscriber based communication  

### 🌐 Simulation Environment
- Robot simulation using Gazebo  
- Testing algorithms before deploying on hardware  

### 🧪 Testing & Prototyping
- Modular structure for experimenting with robotics components  
- Rapid iteration between simulation and real-world execution  

---

## 📁 Project Structure

```
Ros-Robo/
│── test/
│   ├── src/                # Custom ROS 2 package(s)
│   ├── launch/             # Launch files for simulation & nodes
│   ├── scripts/            # Python ROS 2 nodes
│   ├── firmware/           # Arduino / ESP32 code
│   ├── worlds/             # Gazebo simulation worlds
│   ├── urdf/               # Robot description files
```

---

## 🚀 Getting Started

### 1. Prerequisites
- Ubuntu 20.04 / 22.04  
- ROS 2 (Humble recommended)  
- Gazebo installed  

### 2. Clone the Repository
```
git clone https://github.com/Mangal-Devanshu/Ros-Robo.git
cd Ros-Robo/test
```

### 3. Build Workspace
```
colcon build
source install/setup.bash
```

### 4. Run ROS 2 Nodes
```
ros2 run <package_name> <node_name>
```

### 5. Launch Simulation
```
ros2 launch <package_name> <launch_file>.py
```

---

## 🔧 Hardware Integration

- ESP32 / Arduino used for:
  - Motor control  
  - Sensor interfacing  
  - Low-level execution  

- ROS 2 handles:
  - High-level decision making  
  - Communication and coordination  
  - Simulation and visualization  

---

## 🔍 Use Cases

- Bridging simulation and real robotic hardware  
- Testing control pipelines before deployment  
- Developing custom ROS 2 robotic systems  
- Prototyping autonomous mobile robots  

---

## 📈 Future Work

- Integration with perception modules (Computer Vision, OAK-D)  
- Autonomous navigation and path planning  
- Multi-robot coordination  
- Reinforcement learning-based control  

---

## 👨‍💻 Authors

**Devanshu Mangal**  
Robotics | AI/ML | Embedded Systems  

**Dhairya Prajapati**  
Robotics Enthusiast | Embedded Systems  

---

## 📜 License

This project is open-source and available under the MIT License.
