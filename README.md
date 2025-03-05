# ROBOTIC-PATH-PLANNING-FOR-ORB-SLAM-MAP
# Robotic Path Planning for ORB-SLAM Map

This repository contains an implementation of **robotic path planning using an ORB-SLAM-generated map**. The project combines **Simultaneous Localization and Mapping (SLAM)** with **graph-based path planning algorithms** to enable autonomous navigation.

## 📌 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Challenges](#challenges)
- [Future Scope](#future-scope)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## 🚀 Introduction
Autonomous navigation systems rely on **SLAM algorithms** to build maps while simultaneously estimating a robot's position. This project integrates **ORB-SLAM** for map generation and **Dijkstra’s Algorithm** for optimal path planning.

The **goal** is to navigate a robot from a **start position** to a **goal position**, avoiding obstacles and optimizing the path based on real-time ORB-SLAM data.

---

## 🌟 Features
- **ORB-SLAM-based environment mapping**
- **Graph-based shortest path algorithms** (Dijkstra, A*)
- **Occupancy grid representation for path planning**
- **Integration of computer vision (ORB feature detection)**
- **Real-time path computation**
- **Visualization of keypoints, paths, and grid maps**

---

## 🛠️ Technologies Used
- **Python 3.10+**
- **OpenCV** (Computer Vision processing)
- **NumPy** (Mathematical operations)
- **Matplotlib** (Visualization)
- **SciPy** (Distance computation)
- **Heapq** (Priority queue for Dijkstra’s algorithm)

---

## 📥 Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
FUTURE SCOPE:
This work has to get validated and subjected to further improvements.
