# Population Dynamics Modelling (Python)

## Overview

This project implements and analyses **dynamic systems using numerical methods**, with a focus on solving systems of ordinary differential equations (ODEs).

The models simulate interacting populations over time and are used to explore:

* Time-series behaviour
* System stability and equilibrium
* Nonlinear interactions

While inspired by biological systems, the techniques are broadly applicable to **data analysis** and **quantitative modelling**.

---

## Key Skills Demonstrated

* Numerical simulation (Euler method, Runge–Kutta RK4)
* Scientific computing in Python (NumPy, SciPy)
* Time-series analysis and feature extraction
* Data visualisation (Matplotlib)
* Working with multi-variable systems
* Writing structured, modular code for simulations

---

## Project Components

### 1. Predator–Prey Model

Implemented the Lotka–Volterra system to simulate interacting populations.

* Developed numerical solutions using:

  * Euler’s method (manual implementation)
  * `scipy.integrate.solve_ivp` (RK4)

* Analysed:

  * Oscillatory behaviour
  * Long-term system dynamics
  * Phase-space relationships

---

### 2. Numerical Methods Comparison

Compared different numerical approaches to solving ODEs.

* Investigated:

  * Accuracy vs computational cost
  * Impact of step size on stability
  * Error behaviour across methods

This highlights important considerations when implementing simulation-based systems.

---

### 3. Time-Series Analysis

Extracted features from simulated data:

* Peak detection using `scipy.signal.find_peaks`
* Estimation of oscillation periods
* Analysis of repeating patterns

These techniques are relevant to any domain involving **temporal data and pattern detection**.

---

### 4. Multi-State System (Extended Model)

Extended the model to a three-variable interacting system:

* Humans (H)
* Zombies (Z)
* Deceased (D)

This demonstrates:

* Handling higher-dimensional systems
* Modelling state transitions
* Managing more complex dependencies between variables

---

## Computational Methods Used

* Python
* NumPy
* SciPy
* Matplotlib
* Markdowns (including LaTeX)

---

## Example Outputs

* Time evolution plots of system variables
* Phase-space diagrams illustrating system dynamics
* Quantitative estimates of oscillation periods

---

## Why This Project Matters

This project demonstrates the ability to:

* Translate real-world problems into **mathematical and computational models**
* Implement and compare **numerical algorithms**
* Work with **time-series data and extract meaningful features**
* Analyse **nonlinear systems and feedback behaviour**
* Write clear, structured, and reproducible code

## Author

[Amisha B-D]
