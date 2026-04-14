# AI-DWECS: Lightweight Q-Learning Based Task Scheduler for Edge Computing

## Overview
AI-DWECS is an intelligent task scheduling system designed for 5G Mobile Edge Computing (MEC).  
It enhances traditional DWECS by integrating **Q-learning** to dynamically balance **task completion rate** and **energy efficiency**.

---

## Key Features
- Lightweight Q-learning model suitable for edge devices
- Dynamic scheduling using EDF + cost-based optimization
- Handles heterogeneous servers (different CPU & power)
- Optimizes trade-off between **deadline satisfaction** and **energy consumption**

---

## Methodology
- Tasks are scheduled using **EDF (Earliest Deadline First)**
- Q-learning selects optimal weights for:
  - Time (deadline priority)
  - Energy (power efficiency)
- Reward = Task Completion − Energy Penalty

---

## Technologies Used
- Python
- Reinforcement Learning (Q-Learning)
- Edge Computing Simulation
- NumPy, Pandas

---

## Results
- Improved adaptability over static scheduling algorithms
- Efficient performance in dynamic workloads
- Suitable for real-time edge systems

---
## Project Documents
- [Project Report](docs/AI-DWECS_Report.pdf)
- [Presentation Slides](docs/AI-DWECS_Presentation.pptx)
