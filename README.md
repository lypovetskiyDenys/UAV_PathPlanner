# UAV Control System Based on Genetic Algorithms

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![Python](https://img.shields.io/badge/python-3.x-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 📄 About

This repository contains the source code and documentation for my Master's thesis: **"Method of UAV Control Based on Genetic Algorithms"**.

The project focuses on developing and simulating a control system that utilizes genetic algorithms (GA) to optimize flight paths and stabilize UAV behavior under various conditions. By mimicking natural selection processes, the system evolves optimal control parameters to adapt to changing environments and mission requirements.

## 🚀 Features

* **Genetic Algorithm Implementation:** Custom evolutionary strategy for parameter optimization.
* **Flight Simulation:** Python-based environment to test and visualize UAV behavior.
* **Path Planning:** Autonomous route generation avoiding obstacles.
* **Data Analysis:** Tools for evaluating the fitness and convergence of the algorithm.

## 📸 Screenshots

### Simulation Interface
![Simulation View](<img width="468" height="264" alt="image" src="https://github.com/user-attachments/assets/ac50a0ac-1feb-400b-804e-e59e774a20e3" />
)
*Figure 1: Visualization of the UAV flight path generation.*

### Genetic Algorithm Performance
![GA Graphs](path/to/your/screenshot2.png)
*Figure 2: Convergence graph showing fitness score improvement over generations.*

## 🛠️ Technology Stack

* **Language:** Python
* **Libraries:** `NumPy`, `Matplotlib`, `PyGame` (or `SimPy` / `Pandas` - *update based on your exact imports*)
* **Tools:** Jupyter Notebooks (for analysis)

## 🔧 Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/uav-genetic-control.git](https://github.com/your-username/uav-genetic-control.git)
    cd uav-genetic-control
    ```

2.  **Create a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## 💻 Usage

To launch the main simulation:

```bash
python main.py
