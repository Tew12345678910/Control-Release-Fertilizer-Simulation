# Hydrogel Controlled Release Fertilizer Simulation

## Overview
This project implements a numerical simulation of nutrient diffusion from a semi-spherical hydrogel fertilizer in water. It models the diffusion process using a 2D grid in cylindrical coordinates with radial symmetry and visualizes the concentration changes over time.

## Features
- Semi-spherical geometry model with configurable dimensions
- Implementation of diffusion equation in cylindrical coordinates
- Finite difference method with appropriate boundary conditions
- Mass conservation tracking and equilibrium detection
- Various visualizations including 2D plots, 3D surface plots, and animations
- Analysis of Fickian diffusion behavior and release kinetics
- Comparison of different diffusion coefficients and their effects on release rates

## Technical Details
The simulation solves the diffusion equation:
∂C/∂t = D(∂²C/∂r² + (1/r)(∂C/∂r) + ∂²C/∂z²)

It includes:
- Cylindrical coordinates with radial symmetry
- One-way transfer mechanism (hydrogel to water)
- Dynamic equilibrium based on concentration gradients
- Visual representation of diffusion profiles over time

## Usage
Open the Jupyter notebook `hydrogel_fertilizer_simulation.ipynb` to:
1. Adjust model parameters (geometry, diffusion coefficient, etc.)
2. Run the simulation to generate diffusion profiles
3. Explore visualizations of the diffusion process
4. Analyze release kinetics with different parameters

## Author
- Mathus Jirapunyawong

## Course Information
This work was developed for CENG3150, Group 2.
