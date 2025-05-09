# Hodgkin–Huxley Neuron Simulation

This project implements and analyzes the classic **Hodgkin–Huxley model** of action potential generation in neurons using numerical integration techniques. It was completed as part of the *Stochastic Processes and Simulation in Natural Sciences* course during my BSc in Mathematical and Computing Sciences for AI.

## Project Overview

The Hodgkin–Huxley model describes the electrical behavior of excitable cells such as neurons through a system of nonlinear differential equations. This simulation investigates how a neuron responds to:
- Deterministic constant current input
- Stochastic fluctuating current input (e.g. Gaussian noise)

The model tracks the evolution of:
- Membrane potential (V)  
- Gating variables: activation/inactivation of ion channels (`m`, `h`, `n`)  
- Individual ion currents: sodium (Na⁺), potassium (K⁺), and leak channels  

## What’s Included

- `HH-model.ipynb`: Jupyter Notebook with full implementation, plots, and analysis
- Numerical integration via Euler's method  
- Voltage response under different current profiles  
- Spike timing and amplitude comparisons  
- Visualization of gating dynamics and ionic conductances

## Example Plots

- Membrane voltage over time  
- Gating variable trajectories  
- Comparison between deterministic and stochastic simulations  

## How to Run

1. Open `HH-model.ipynb` in Jupyter Notebook or JupyterLab  
2. Install required packages if needed:
```bash
pip install numpy matplotlib
```
3.	Run the notebook to simulate and visualize neuron dynamics
