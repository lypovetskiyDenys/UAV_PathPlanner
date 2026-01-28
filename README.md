# UAV Control System Based on Genetic Algorithms

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![Python](https://img.shields.io/badge/python-3.x-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## About

This repository contains the source code and documentation 

For my Master's thesis: 

**"Method of UAV Control Based on Genetic Algorithms"**.

The project focuses on developing and simulating a control system that utilizes genetic algorithms (GA) to optimize flight paths and stabilize UAV behavior under various conditions. By mimicking natural selection processes, the system evolves optimal control parameters to adapt to changing environments and mission requirements.

## Features

* **Genetic Algorithm Implementation:** Custom evolutionary strategy for parameter optimization.
* **Flight Simulation:** Python-based environment to test and visualize UAV behavior.
* **Path Planning:** Autonomous route generation avoiding obstacles.
* **Data Analysis:** Tools for evaluating the fitness and convergence of the algorithm.

## Screenshots

### Simulation Interface
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/a7dd1183-2bd5-4900-981e-8bd401231d7e" />

*Figure 1: Visualization of the UAV flight path generation.*

<img width="1048" height="919" alt="image" src="https://github.com/user-attachments/assets/ae89ea46-81bf-40f7-b2bf-a0593b4a1549" />

*Figure 2: 3D path representation*

<img width="419" height="1430" alt="image" src="https://github.com/user-attachments/assets/daeccadf-49e4-4312-9632-cb946527577d" />

*Figure 3: Control Menu*

<img width="456" height="1297" alt="image" src="https://github.com/user-attachments/assets/c08312d5-902d-43a4-a334-8f31460b6c69" />

*Figure 4: 2D projections*

<img width="2084" height="1298" alt="image" src="https://github.com/user-attachments/assets/6c860461-4bd4-4eda-ac1b-b9d60445454c" />

*Figure 5: Performance*

<img width="2084" height="1309" alt="image" src="https://github.com/user-attachments/assets/13315b73-b0c4-4bc4-a909-b792bb9aed23" />

*Figure 6: Trajectory*

<img width="2077" height="1352" alt="image" src="https://github.com/user-attachments/assets/312a4d9a-782e-4076-89f6-3ebd561f0de2" />

*Figure 7: Statistics*

<img width="415" height="1389" alt="image" src="https://github.com/user-attachments/assets/62157869-c902-4faa-94e2-124d6c5cc39d" />

*Figure 8: Hint*

## Otput:


[01:01:19] Starting GA: pop=100, gens=200, strategy=Convergence (GaCPo)

[01:01:33] Gen 5: cost=63532.1, coll=2

[01:01:33] Gen 10: First collision-free solution found!

[01:01:35] Gen 10: improved by 47264.2 -> cost=16267.9
[01:01:37] Gen 15: improved by 3684.4 -> cost=12583.5
[01:01:40] Gen 20: improved by 4355.2 -> cost=8228.3
[01:01:42] Gen 25: improved by 592.0 -> cost=7636.3
[01:01:44] Gen 30: improved by 542.6 -> cost=7093.7
[01:01:47] Gen 35: improved by 291.2 -> cost=6802.5
[01:01:49] Gen 40: improved by 1542.9 -> cost=5259.6
[01:01:51] Gen 45: improved by 111.2 -> cost=5148.4
[01:01:54] Gen 50: improved by 132.4 -> cost=5015.9
[01:01:56] Gen 55: improved by 345.5 -> cost=4670.4
[01:01:59] Gen 60: improved by 323.6 -> cost=4346.8
[01:02:01] Gen 65: improved by 132.6 -> cost=4214.2
[01:02:11] Gen 85: improved by 256.1 -> cost=3958.1
[01:02:16] Gen 95: improved by 214.8 -> cost=3743.4

[01:02:21] Gen 105: improved by 200.0 -> cost=3543.4
[01:02:32] Gen 125: improved by 29.2 -> cost=3514.2
[01:02:46] Gen 150: improved by 149.2 -> cost=3365.0
[01:03:00] Gen 175: improved by 69.9 -> cost=3295.1
[01:03:09] Gen 190: improved by 6.8 -> cost=3288.4

[01:03:16] GA finished! Final cost=3288.37, collisions=0

[01:03:16] Path smoothed with 200 points


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
