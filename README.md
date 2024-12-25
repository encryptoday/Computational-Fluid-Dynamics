# Natural Convection in a Cavity with a Wavy Cylinder

This repository contains the code, models, and visualizations for a **Computational Fluid Dynamics (CFD)** project that investigates fluid flow and heat transfer in curve-shaped cavities with a wavy cylinder inside. The project evaluates the influence of internal heat absorption, buoyancy-driven convection, and various dimensionless parameters on the fluid dynamics and heat distribution within the cavity.

## Project Overview

The goal of this study is to:
1. Solve fluid flow problems in curve-shaped cavities containing a wavy cylinder.
2. Evaluate the effects of internal heat absorption and buoyancy-driven natural convection.
3. Analyze the impact of dimensionless parameters such as Rayleigh number, Reynolds number, and Hartmann number on the flow field, heat transfer, and temperature distribution.

### Key Features
- The model is evaluated under conditions where:
  - The bottom and top walls are partially heated.
  - The fluid is considered laminar, with convection generated solely by buoyancy forces.
- A numerical approach is applied using:
  - **Galerkin weighted residual method of finite elements**.
  - Software tools including **COMSOL Multiphysics**, **MATLAB**, and **Tecplot**.
- Results include visualizations of streamlines and isotherms, showcasing the influence of dimensionless parameters on flow and heat transfer.

## Methodology

1. **Mathematical Modelling**:
   - Dimensionless governing equations for natural convection are derived and solved.
   - Dimensionless parameters (e.g., Rayleigh number, Reynolds number, Hartmann number) are introduced to study their effects.

2. **Numerical Solution**:
   - The problem is solved using the Galerkin weighted residual method implemented in COMSOL Multiphysics.
   - MATLAB is used for data processing, and Tecplot is employed for visualization.

3. **Analysis**:
   - The impact of heat generation and absorption is analyzed.
   - Streamlines and isotherms are plotted to evaluate changes in fluid flow and heat transfer under varying conditions.

## Results

- The study highlights significant effects of dimensionless parameters on:
  - **Flow Field**: Streamline patterns change significantly with variations in parameters.
  - **Heat Transfer**: Temperature distribution and heat transfer rates are influenced by heat generation and absorption.
  - **Isotherms**: Visualizations reveal the impact of Rayleigh number and other parameters on thermal gradients.

## Tools and Technologies

- **COMSOL Multiphysics**: Used for developing the model and solving the governing equations.
- **MATLAB**: Used for processing numerical results and generating data for visualization.
- **Tecplot**: Used for creating detailed plots of streamlines and isotherms.

## Repository Contents

- `models/`: COMSOL model files for different configurations.
- `scripts/`: MATLAB scripts for data analysis and processing.
- `visualizations/`: Plots of streamlines, isotherms, and other visual outputs.
- `docs/`: Detailed documentation and results analysis.
- `README.md`: This file.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cfd-wavy-cylinder.git
   cd cfd-wavy-cylinder
