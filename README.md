# LBM-Simulation

## Description
This repository contains a Python-based implementation of the Lattice Boltzmann Method (LBM) for simulating fluid dynamics. The code utilizes powerful libraries like NumPy for numerical computations and Matplotlib for visualizing results. It is designed to be flexible and customizable, making it suitable for research in computational physics and fluid mechanics.

## Features
- **Customizable Parameters**: Configure grid dimensions, relaxation time, and simulation duration.
- **Optimized Performance**: Uses NumPy for efficient and fast computations.
- **Visualization Tools**: Generate insightful plots of fluid flow with Matplotlib.
- **Extensible Codebase**: Modular functions for easy customization and further development.

## Requirements
- Python 3.8 or later
- NumPy
- Matplotlib

## Installation
1. Clone the repository and navigate to the project directory:
   ```bash
   git clone https://github.com/AmineSlimani/LBM-Simulation.git
   cd LBM-Simulation
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Open the Jupyter Notebook file `Amine_Slimani.ipynb` to explore and execute the simulation. The notebook allows you to:
- Modify simulation parameters, such as grid size, relaxation time, and number of time steps.
- Run the simulation to observe fluid dynamics behavior.

### Example Parameters
You can adjust the following parameters in the notebook:
```python
Nt = 1000  # Number of time steps
tau = 0.8  # Relaxation time
Nx, Ny = 102, 22  # Grid dimensions
```
Run all cells to see the results, including visualizations of the fluid flow.

## Contributing
We welcome contributions! If you have suggestions, improvements, or bug fixes, feel free to fork the repository and create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments
- Inspired by advanced computational physics and fluid mechanics research.
- Special thanks to the Python community for providing robust libraries like NumPy and Matplotlib.

