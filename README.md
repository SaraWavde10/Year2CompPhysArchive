# Computational Physics Projects

This repository contains three computational physics projects completed as part of the PHYS20762 course. Each project demonstrates different numerical techniques and physical simulations using Python in Jupyter notebooks.

---

## Projects Overview

### Project 1: Droplet Spreading Analysis

Analysis of experimental data from picolitre droplet spreading on a flat substrate to determine the empirical spreading law.

**Key techniques:**
- Data loading and visualization with error bars
- Solving implicit equations using the spherical cap approximation to relate droplet radius to contact angle
- Computing contact line speeds from experimental data
- Fitting Cox-Voinov and de Gennes spreading laws using polynomial regression
- Chi-squared analysis and residual examination
- Cubic spline interpolation for non-uniformly distributed data

**Physics concepts:** Contact line dynamics, wetting phenomena, spreading laws, error propagation

---

### Project 2: Spring-Mass System Simulations

Numerical study of a damped harmonic oscillator with external forcing, comparing multiple integration methods.

**Key techniques:**
- Implementation of four numerical methods: Euler, Improved Euler (Heun), Verlet, and Euler-Cromer
- Comparison of numerical accuracy against analytical solutions
- Time step convergence studies
- Energy conservation analysis
- Investigation of underdamped, critically damped, and overdamped regimes
- Forced oscillations and resonance studies

**Physics concepts:** Damped harmonic motion, resonance, numerical stability, energy conservation

---

### Project 3: Neutron Transport Monte Carlo

Monte Carlo simulation of neutron absorption and scattering through shielding layers of water, lead, and graphite.

**Key techniques:**
- Random number generation and uniformity testing
- Exponential distribution sampling for mean free path
- Isotropic unit vector generation in 3D
- Monte Carlo random walk simulation with absorption, reflection, and transmission tracking
- Macroscopic cross-section calculations from nuclear data
- Attenuation length determination via exponential fitting
- Woodcock method for multi-layer shielding

**Physics concepts:** Neutron transport, scattering and absorption cross-sections, mean free path, exponential attenuation, Monte Carlo methods

---

## Repository Structure
├── phys20762_project1.ipynb # Droplet spreading analysis
├── phys20762_project2.ipynb # Spring-mass system simulations
├── phys20762_project3.ipynb # Neutron transport Monte Carlo
├── data/ # Experimental data files (Project 1)
│ ├── experimental_run1.txt
│ ├── experimental_run2.txt
│ └── experimental_run3.txt
└── README.md


---

## Requirements

All notebooks require Python 3.7+ with the following packages:

```bash
pip install numpy matplotlib scipy ipympl


Note: This README.md was AI generated, prompted by me 
