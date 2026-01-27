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
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/a7dd1183-2bd5-4900-981e-8bd401231d7e" />

*Figure 1: Visualization of the UAV flight path generation.*

<img width="1048" height="919" alt="image" src="https://github.com/user-attachments/assets/ae89ea46-81bf-40f7-b2bf-a0593b4a1549" />

*Figure 2: 3D path representation*

<img width="456" height="1297" alt="image" src="https://github.com/user-attachments/assets/c08312d5-902d-43a4-a334-8f31460b6c69" />

*Figure 3: 2D projections*

<img width="2084" height="1298" alt="image" src="https://github.com/user-attachments/assets/6c860461-4bd4-4eda-ac1b-b9d60445454c" />

*Figure 4: Performance*


### Genetic Algorithm Performance
![GA Graphs](path/to/your/screenshot2.png)
*Figure 4: Convergence graph showing fitness score improvement over generations.*

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
