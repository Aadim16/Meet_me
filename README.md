# 🚦 Visual Pathfinding with Dijkstra + Computer Vision

## 🧠 Project Overview
This project blends the power of **Dijkstra’s Algorithm**, **Computer Vision**, and **Graph Theory** to turn ordinary images into intelligent pathfinding systems.

By uploading an image with:

* ⚪ **Circles** representing **nodes** (e.g., hospitals, junctions, meetup points)
* ➖ **Lines** representing **edges** (with visible weights)

The system:

* Automatically detects the nodes and paths using **OpenCV** and **Hough Transforms**
* Constructs a graph using **NetworkX**
* Computes the **shortest path** between any two nodes using **Dijkstra’s Algorithm**
* Visually highlights the computed path over the original image

This can be applied in real-world use cases such as:

* 🚑 **Ambulance routing** to the nearest hospital
* 🧭 **Campus or facility navigation**
* 🧑‍🤝‍🧑 **Friend-finder or clan-based path planning**
* 🏙️ **Smart city map understanding from visual input**

---

## ⚙️ Tech Stack

* **Python 3**
* **OpenCV** – for image processing
* **NumPy** – for data handling
* **NetworkX** – for graph operations and visualization

## 📌 How It Works

1. Upload a clear image with **circles** (nodes) and **lines** (edges).
2. The program detects nodes and edges using OpenCV.
3. A weighted graph is built from the visual layout.
4. The shortest path between any two selected nodes is computed using Dijkstra's Algorithm.
5. The result is overlaid back on the image, clearly marking the path.

> **Note:** The current system supports images where nodes are circular and edges are straight lines with visible weights.

---
## 📄 License & Copyright

© 2025 Aditya Mangla. All rights reserved.

This project is licensed for educational and personal use only.
Unauthorized commercial use, redistribution, or reproduction of any part of this project without explicit permission is strictly prohibited.

For collaborations, feature contributions, or licensing inquiries, feel free to reach out.
