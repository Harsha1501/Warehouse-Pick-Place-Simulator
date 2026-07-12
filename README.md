# 🤖 Warehouse Pick-and-Place Robot Simulator

A Python-based warehouse automation simulator that demonstrates autonomous robot navigation, A* path planning, obstacle avoidance, animated robot movement, package pickup, package delivery, and task reporting.

---

## 📌 Project Overview

This project simulates an autonomous warehouse robot that transports a package from a pickup location to a delivery destination while avoiding obstacles (warehouse shelves).

The robot:

- Navigates inside a warehouse
- Finds the shortest collision-free path using A*
- Picks up a package
- Delivers the package to a target location
- Animates the robot's movement
- Generates a mission report
- Exports results as JSON

This project demonstrates fundamental robotics concepts used in warehouse automation systems.

---

## 🚀 Features

- Warehouse Environment Simulation
- Autonomous Robot Navigation
- A* Path Planning
- Obstacle Avoidance
- Package Pickup
- Package Delivery
- Animated Robot Movement
- Mission Statistics
- JSON Report Export
- Visualization using Matplotlib

---

## 🛠 Technologies Used

- Python 3
- NumPy
- Matplotlib
- JSON
- Google Colab / Jupyter Notebook

---

## 📂 Project Structure

```text
warehouse-pick-place-simulator/
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── notebook/
│   └── Warehouse_Pick_Place.ipynb
│
├── outputs/
│   ├── warehouse_result.png
│   └── task_report.json
│
└── screenshots/
    ├── 01_warehouse_layout.png
    ├── 02_astar_path.png
    ├── 03_robot_animation.png
    ├── 04_box_picked.png
    ├── 05_box_delivered.png
    ├── 06_final_warehouse.png
    
```

---

## ⚙ Workflow

```
Initialize Warehouse
        │
        ▼
Create Obstacles
        │
        ▼
Place Robot
        │
        ▼
Place Package
        │
        ▼
Place Delivery Target
        │
        ▼
A* Path Planning
        │
        ▼
Navigate to Package
        │
        ▼
Pick Package
        │
        ▼
Navigate to Target
        │
        ▼
Deliver Package
        │
        ▼
Generate Report
        │
        ▼
Export JSON
```

---

## 📊 Sample Output

```
MISSION REPORT
----------------------------
Package Picked     : Yes
Package Delivered  : Yes
Path Planning      : A*
Collision Free     : Yes
Mission Status     : Success
```

---

## 📄 Sample JSON

```json
{
    "algorithm": "A*",
    "package_picked": true,
    "package_delivered": true,
    "collision_free": true,
    "status": "Success"
}
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/Harsha1501/warehouse-pick-place-simulator.git
```

Move into the project directory:

```bash
cd warehouse-pick-place-simulator
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
notebook/Warehouse_Pick_Place.ipynb
```

Run all cells.

---

## 🎯 Learning Outcomes

This project demonstrates:

- Robot Navigation
- A* Search Algorithm
- Path Planning
- Obstacle Avoidance
- Warehouse Automation
- Robot Simulation
- Python Programming
- Data Visualization

---

## 🚀 Future Improvements

- Multi-Robot Coordination
- Dynamic Obstacles
- Battery Monitoring
- Reinforcement Learning
- ROS 2 Integration
- SLAM Mapping
- Real Warehouse Maps
- Live Camera Input

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Harsha**

GitHub: https://github.com/Harsha1501