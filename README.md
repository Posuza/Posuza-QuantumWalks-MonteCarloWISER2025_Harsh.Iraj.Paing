# Quantum Walks and Monte Carlo Methods

## Overview

This repository contains the work of the Womain Quantum Wisner student group for the Wiser 2025 project. Developed by Harshi, Iraj, and Paing, the project focuses on the implementation and analysis of Quantum Walks and Monte Carlo methods. The core objective is to reproduce and analyze a foundational research paper, providing a structured, step-by-step approach to quantum simulation and analysis.

## Project Description

This project investigates the intersection of quantum walks and Monte Carlo methods, leveraging quantum computing to simulate and analyze probabilistic processes. Quantum walks are the quantum analog of classical random walks and have applications in quantum algorithms, search, and simulation. Monte Carlo methods are widely used for statistical sampling and numerical analysis.

The main goals of this project are:

- Implement quantum walk circuits using Qiskit, including both unbiased (Hadamard) and biased walks.
- Simulate these circuits and compare quantum results to classical theoretical distributions (binomial, Gaussian, exponential).
- Explore the impact of noise on quantum simulations using realistic noise models and fake hardware backends.
- Apply Monte Carlo techniques for statistical analysis and uncertainty quantification, including bootstrapping and total variation distance (TVD) calculations.
- Reproduce and analyze results from a foundational research paper, providing a clear, step-by-step methodology for quantum simulation and analysis.

The repository includes a Jupyter notebook with code for circuit construction, simulation, visualization, and quantitative analysis, as well as a project plan document outlining the research objectives and approach.

## Getting Started

### Prerequisites

To run the project code, you will need the following Python libraries:

- qiskit
- qiskit-aer
- matplotlib
- scipy
- numpy

### Installation

Install the required dependencies using pip:
```bash
!pip install qiskit qiskit-aer matplotlib scipy numpy
```

Additionally, install Qiskit community packages:
```bash
!pip install git+https://github.com/qiskit-community/qiskit-algorithms
!pip install git+https://github.com/qiskit-community/qiskit-research
```

## Project Structure

- `QW_MC.ipynb`: Jupyter Notebook containing the main implementation, including code for quantum walks, noise models, simulation, and visualization.
- `Documentation.pdf`: Document outlining the project plan, goals, and methodological breakdown.

## Usage

Open the notebook `QW_MC.ipynb` and run the cells sequentially to:

- Build and simulate quantum Galton board circuits
- Analyze quantum walks and Monte Carlo methods
- Visualize results and compare to theoretical distributions
- Explore the effects of noise and perform quantitative analysis

## Team Members

- Harshita Singh
- Iraj Masood
- Paing Hein Thet Mon

## Reference Article

- arXiv.org: https://arxiv.org/abs/2202.01735


## References

- [Qiskit Documentation](https://qiskit.org/documentation/)
- [Quantum Walks](https://en.wikipedia.org/wiki/Quantum_walk)
- [Galton Board](https://en.wikipedia.org/wiki/Bean_machine)
