# Steinschlagchallenge CWM1

## Project Overview
This project simulates the failure of safety nets based on accumulated mass and impact energy over time. It aims to predict when and under what conditions the nets will fail, providing crucial data to improve safety measures.

## Features
- **Monte Carlo Simulation**: Generates synthetic datasets for mass, velocity, and time intervals to simulate real-world scenarios.
- **Energy Calculation**: Computes the kinetic energy based on mass and velocity to assess the potential for net failure.
- **Failure Detection**: Evaluates whether the accumulated mass and impact energy at each step exceed safety thresholds.
- **Visualization**: Provides visual representations of failure events over time to analyze trends and identify critical points.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- Python 3.8 or higher
- Libraries: numpy, matplotlib, pandas, seaborn, fitter, scipy

### Installation
1. **Install pipenv:**
    pip install pipenv

2. **Clone the repository:**
    git clone https://github.com/Steff72/cwm1

3.	**Install required packages and activate environment:** 
    pipenv install
    
4. **To activate environment:**
    pipenv shell

### How It Works

1.	Data Generation: Synthetic data for mass, velocity, and time intervals is generated using predefined distributions.
2.	Simulation Execution: The program iterates through the generated data, calculating kinetic energy and accumulating mass, to determine when the safety nets will fail.
3.	Visualization: After the simulation, use the provided visualization scripts to plot the failure events and energy levels over time.

### License
This project is licensed under the MIT License.

### Acknowledgments
Github Copilot was used to build the code.