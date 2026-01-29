# UAV Genetic Algorithm Path Planner

![Status](https://img.shields.io/badge/status-active-success.svg)
![Python](https://img.shields.io/badge/python-3.13%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

<br/>
<div align="center">
    <img src="https://github.com/user-attachments/assets/ae89ea46-81bf-40f7-b2bf-a0593b4a1549" width="100%" style="border-radius: 10px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);">
</div>
<br/>

## 📄 About

This repository contains the source code for my Master's thesis: **"Method of UAV Control Based on Genetic Algorithms"**.

The project is a comprehensive **3D path planning application** featuring a real-time PyQt6 GUI. It implements a waypoint-based genetic algorithm inspired by the research of *Gutierrez-Martinez et al. (2025)*. The system evolves optimal flight paths through complex 3D environments with spherical obstacles, balancing multiple conflicting objectives:

* **Path Length** (minimization)
* **Collision Avoidance** (safety penalties)
* **Path Smoothness** (curvature minimization)
* **Energy Efficiency** (altitude/turn costs)

## 🛠 Tech Stack

<div style="display:flex; gap:10px; flex-wrap:wrap;">
    <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /></a>
    <a href="https://riverbankcomputing.com/software/pyqt/intro"><img src="https://img.shields.io/badge/PyQt6-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt6" /></a>
    <a href="https://numpy.org/"><img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" /></a>
    <a href="https://scipy.org/"><img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy" /></a>
    <a href="https://matplotlib.org/"><img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib" /></a>
</div>

## 🚀 Features

* **Multi-Strategy Optimization:** Choose between `GaLM` (Standard), `GaHM` (High Mutation), and `GaCPo` (Convergence) strategies.
* **Interactive GUI:** Real-time parameter tuning (mutation rates, population size) without restarting the app.
* **Dynamic Environment:** Support for moving obstacles that shift position during optimization.
* **Rich Visualization:** * 3D Interactive Plot
    * 2D Projections (Top-down/Side views)
    * Real-time fitness & convergence graphs
* **Export Tools:** Save calculated paths to CSV and high-res figures to PNG.

## 📸 Interface & Visualization

### Main Dashboard
<img src="https://github.com/user-attachments/assets/a7dd1183-2bd5-4900-981e-8bd401231d7e" width="100%" style="border-radius: 5px;">
*The main application window featuring 3D visualization, log console, and control tabs.*

### Analysis Views
<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>2D Projections</b><br/>
      <img src="https://github.com/user-attachments/assets/c08312d5-902d-43a4-a334-8f31460b6c69" width="100%">
    </td>
    <td width="50%" align="center">
      <b>Algorithm Performance</b><br/>
      <img src="https://github.com/user-attachments/assets/6c860461-4bd4-4eda-ac1b-b9d60445454c" width="100%">
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <b>Trajectory Analysis</b><br/>
      <img src="https://github.com/user-attachments/assets/13315b73-b0c4-4bc4-a909-b792bb9aed23" width="100%">
    </td>
    <td width="50%" align="center">
      <b>Statistics</b><br/>
      <img src="https://github.com/user-attachments/assets/312a4d9a-782e-4076-89f6-3ebd561f0de2" width="100%">
    </td>
  </tr>
</table>

## 📂 Project Structure

```bash
├── main.py                 # Entry point (MainWindow & Logic)
├── pyproject.toml          # Dependencies & Config
├── README.md               # Documentation
├── uv.lock                 # Lock file for dependencies
├── assets/                 # Images and resources
└── src/                    # (Logical structure)
    ├── Environment         # Obstacles and boundary definitions
    ├── GeneticPlanner      # Core GA logic and fitness functions
    └── GAWorker            # QThread for background processing
