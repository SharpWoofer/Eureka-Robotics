# 2D Motion Planning and Path Post-processing

Welcome to the repository containing solutions for the 2D motion planning and path post-processing exercises. These tasks were part of an assignment to demonstrate proficiency in implementing and evaluating algorithms for motion planning and path optimization.

Dockerfile is available [here](https://github.com/nicholasadr/dockerfiles/tree/master/osrobotics-kinetic).

## 📝 Overview

This repository includes solutions for two key exercises:

1. **Exercise 1: Solving a 2D Motion Planning Problem Using PRM**
2. **Exercise 2: Post-processing a 2D Path**

The solutions are implemented in Python, and the code is organized in a Jupyter Notebook for clarity and ease of use.

## 🔗 [View the Jupyter Notebook](https://github.com/SharpWoofer/Eureka-Robotics/blob/master/Probabilistic%20Roadmap%20(PRM).ipynb)

## 🚀 Getting Started

### Prerequisites

To run the provided code, ensure you have the following Python packages installed:

- `numpy`
- `matplotlib`
- `pylab`
- `osr_examples` (for the environment setup)

You can install these packages using pip:

```bash
pip install numpy matplotlib pylab
```

## Setup

### 1. Clone the Repository:

```bash
git clone https://github.com/SharpWoofer/2d-motion-Eureka-Robotics.git
cd 2d-motion-Eureka-Robotics
```

### 2. Environment Setup:

```bash
import numpy as np
import pylab as pl
import sys
sys.path.append('osr_examples/scripts/')
import environment_2d
```

## 🧩 Exercises

### Exercise 1: Solving a 2D Motion Planning Problem Using PRM

**Objective:** Implement the Probabilistic Roadmap (PRM) algorithm to solve a 2D motion planning problem.

**Details:**
- Loaded a simple 2D environment containing triangular obstacles.
- Implemented PRM to find collision-free paths from a start configuration to a goal configuration.
- The code generates environments and queries to test the PRM implementation.

**Key Components:**
- PRM Algorithm Implementation
- Environment Generation and Visualization
- Path Finding and Query Testing

### Exercise 2: Post-processing a 2D Path

**Objective:** Implement path shortcutting to improve the length of the paths found using PRM.

**Details:**
- Implemented a shortcutting algorithm to reduce the length of the paths.
- Applied the shortcutting technique to enhance the paths found by PRM.
- Evaluated the quality of the path after applying the shortcutting process.

**Key Components:**
- Path Shortcutting Algorithm Implementation
- Path Length Optimization
- Visualization of the Improved Paths

## 🔍 Results

The results of the exercises, including plots and path visualizations, can be found in the Jupyter Notebook. The notebook includes:
- Code snippets for both exercises
- Generated environments
- Pathfinding results
- Path optimization outcomes

## 📂 Repository Structure

- `Probabilistic Roadmap (PRM).ipynb` - The Jupyter Notebook containing the solutions to both exercises.
- `README.md` - This file, providing an overview and instructions.

## 📄 License

This repository is licensed under the MIT License. See the [LICENSE](https://github.com/SharpWoofer/Eureka-Robotics/blob/master/LICENSE) file for details.

## 🙏 Acknowledgements

Special thanks to [Eureka Robotics](https://eurekarobotics.com/) for providing me with the opportunity to work on this assignment. 
