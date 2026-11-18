# Quadcopter Input Shaping Simulation

## Overview

This project studies the application of **Input Shaping** to reduce payload oscillations in a quadcopter system using MATLAB and Simulink.

The simulation compares the system response under different input shaping methods to observe their effects on payload swing behavior.

## Objectives

- Simulate a quadcopter system with a suspended payload.
- Investigate payload swing behavior during system motion.
- Compare the response of an unshaped system with input shaping methods.
- Explore vibration reduction using different input shapers.

## Input Shaping Methods

The following configurations are included in this project:

- **Unshaped:** Baseline system without input shaping.
- **ZV (Zero Vibration):** Input shaper designed to reduce residual vibration.
- **ZVD (Zero Vibration and Derivative):** Input shaper designed to improve robustness to parameter variations.

## Simulation Results

The simulation results include comparisons between different input shaping configurations.

### Combined Comparison

The following figure compares the simulation responses for different configurations.

![Input Shaping Comparison](results/ALL_0.75.jpg)

### Unshaped System

Baseline response without input shaping.

![Unshaped Response](results/Unshaped_0.75.jpg)

### ZV Input Shaping

Response using the Zero Vibration (ZV) input shaper.

![ZV Response](results/ZV_0.75.jpg)

### ZVD Input Shaping

Response using the Zero Vibration and Derivative (ZVD) input shaper.

![ZVD Response](results/ZVD_0.75.jpg)

## Software

- MATLAB
- Simulink
- Simscape Multibody
## Repository Structure

```text
quadcopter-simulation/
│
├── README.md
│
├── model/
│   ├── quadcopter_model.slx
│   └── matlab.mat
│
└── results/
    ├── ALL_0.75.jpg
    ├── Unshaped_0.75.jpg
    ├── Unshaped_0.35.jpg
    ├── Unshaped_0.45.jpg
    ├── Unshaped_0.55.jpg
    ├── Unshaped_0.65.jpg
    ├── Unshaped_0.75.jpg
    ├── ZV_0.75.jpg
    └── ZVD_0.75.jpg
```

## Notes

This repository is a simulation-based engineering project for studying quadcopter dynamics and input shaping techniques.

The project may be further developed through additional simulations, parameter comparisons, and analysis of payload oscillation behavior.

---

**Project:** Quadcopter Simulation – Input Shaping  
**Tools:** MATLAB, Simulink, Simscape Multibody
