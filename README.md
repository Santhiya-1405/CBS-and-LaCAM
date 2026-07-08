# Multi-Agent Path Finding (MAPF) using Conflict-Based Search (CBS)

## Overview

This project implements the Conflict-Based Search (CBS) algorithm for solving the Multi-Agent Path Finding (MAPF) problem in a 2D grid environment. Multiple agents navigate from their start locations to their respective goal locations while avoiding collisions.

The project provides an interactive graphical interface built using Pygame where users can:

- Create multiple agents
- Assign start and goal positions
- Add obstacles
- Visualize agent movement
- Detect and resolve conflicts using CBS

---

## Features

- Conflict-Based Search (CBS)
- A* Low-Level Path Planner
- Interactive Grid Environment
- Unlimited Agent Support
- Obstacle Placement
- Collision Detection
- Real-Time Visualization
- Different Colors for Agents
- Makespan and Path Cost Calculation

---

## Project Structure

```
mapf_folder_fixed/
│
├── main.py              # Main program
├── cbs.py               # CBS algorithm
├── astar.py             # A* search
├── ui.py                # User Interface
├── config.py            # Configuration values
└── color_utils.py       # Agent colors
```

---

## Requirements

- Python 3.10+
- Pygame

Install dependencies:

```bash
pip install pygame
```

---

## Running the Project

```bash
python main.py
```

---

## CBS Workflow

1. Create agents
2. Assign start and goal positions
3. Plan shortest paths using A*
4. Detect conflicts
5. Add constraints
6. Re-plan affected agent
7. Repeat until conflict-free paths are found

---

## Algorithm Used

- A* Search
- Conflict-Based Search (CBS)

---

## Applications

- Warehouse Robotics
- Autonomous Vehicles
- Drone Coordination
- Factory Automation
- Game AI

---

# Multi-Agent Path Finding (MAPF) using LaCAM

## Overview

This project implements the LaCAM (Lazy Constraint Addition Method) algorithm for solving the Multi-Agent Path Finding (MAPF) problem.

Unlike Conflict-Based Search (CBS), LaCAM efficiently resolves conflicts by using Priority Inheritance with Backtracking (PIBT), making it suitable for environments with many agents.

The project provides an interactive visualization where users can create agents, assign start and goal positions, place obstacles, and observe conflict-free navigation.

---

## Features

- LaCAM Algorithm
- PIBT (Priority Inheritance with Backtracking)
- A* Search
- Interactive GUI using Pygame
- Multiple Agents
- Obstacle Placement
- Real-Time Simulation
- Collision Avoidance
- Efficient Conflict Resolution

---

## Project Structure

```
lacam_folder/
│
├── main.py
├── lacam.py
├── pibt.py
├── cbs.py
├── astar.py
├── distance_table.py
├── ui.py
├── config.py
└── color_utils.py
```

---

## Requirements

- Python 3.10+
- Pygame

Install dependency:

```bash
pip install pygame
```

---

## Running the Project

```bash
python main.py
```

---

## LaCAM Workflow

1. Create agents
2. Select start and goal positions
3. Compute shortest paths
4. Detect conflicts
5. Resolve conflicts using PIBT
6. Continue until all agents reach their goals

---

## Algorithms Used

- LaCAM
- PIBT
- A* Search

---

## Applications

- Warehouse Robots
- AGV Navigation
- Smart Logistics
- Factory Automation
- Multi-Robot Coordination

---

## Advantages of LaCAM

- Faster for large numbers of agents
- Lower planning overhead
- Efficient conflict handling
- Scalable for dense environments
- Real-time path planning

---
