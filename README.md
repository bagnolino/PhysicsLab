# PhysicsLab Repository

This repository contains analysis and results from physics experiments conducted for the "Physics Experiments 2" course. Each experiment is organized in its own directory with standardized structure for data, code, and results.

## Repository Structure

```
physics-experiments/
├── utils/                     # Shared utility functions
│   ├── plotting.py            # Common plotting functions
│   ├── data_processing.py     # Data preprocessing utilities
│   └── error_analysis.py      # Error calculation and propagation
│
├── Experiment1/               # Specific experiment folder
│   ├── README.md              # Experiment-specific documentation
│   ├── input/                 # Raw data files
│   ├── output/                # Results, graphs, processed data
│   └── code/                  # Analysis scripts and notebooks
│       ├── experiment1_analysis.ipynb
│       └── specific_functions.py
│
├── Experiment2/
│   ├── ...
```

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Required packages listed in `requirements.txt`

### Installation

Clone the repository and install required dependencies:

```bash
git clone https://github.com/yourusername/physics-experiments.git
cd physics-experiments
pip install -r requirements.txt
```

## Experiments

Below is a list of experiments included in this repository:

1. **RLC in time** - Analysis of a RLC circuit in the domain of time
2. **RC in frequency** - Analysis of a RC circuit in the domain of frequency

Each experiment folder contains its own README with detailed information about the specific experiment, methodology, and results.

## Utility Functions

The `utils` folder contains reusable functions that are common across different experiments:

- **plotting.py**: Functions for creating standardized plots and visualizations
- **data_processing.py**: Tools for data cleaning, filtering, and transformation
- **error_analysis.py**: Functions for error propagation and uncertainty calculations

## Course Information

This repository contains work for the Physics Experiments 2 course, which is part of the bachelor's degree in Physics at the University of Padua.
[Course link](https://en.didattica.unipd.it/off/2023/LT/SC/SC1158/000ZZ/SCP3050166/A1301)


## Contact

Davide Bagnoli 
Personal Email: bagnolidavide04@gmail.com
Student Email: davide.bagnoli@studenti.unipd.it

Project Link: [https://github.com/yourusername/physics-experiments](https://github.com/yourusername/physics-experiments)
