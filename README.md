# Comparative Analysis of SMART, SMARTS and TVK Methods

Implementation and comparative analysis of SMART, SMARTS, and TVK decision-making methods in Python based on Podinovskiy (2022)

## Authors
- Majd Nakhla  
- Vadim G. Pak  
- Vladimir Parkhomenko  

## Description
This repository contains the full computational implementation accompanying the research paper:

"Comparative Analysis of SMART, SMARTS and TVK Methods"

The project provides a reproducible computational framework for comparing multiple multi-criteria decision-making (MCDM) methods, including:

- SMART (Simple Multi-Attribute Rating Technique)
- SMARTS (with non-uniform weights)
- TVK-based dominance procedures
- Interval Linear Programming dominance
- Analytical interval method
- Monte Carlo simulation

All methods are applied consistently to identical datasets, including:
- E-book reader selection problem
- Hostel selection problem
- PrefLib dataset

The goal of the project is not to enforce agreement between methods, but to analyze how different modeling assumptions affect ranking outcomes and robustness.

## Features
- Unified normalization framework
- λ-based weight construction (Podinovskiy, 2022)
- Interval dominance modeling
- Monte Carlo robustness analysis
- TVK cascade implementation using PyDASS
- Kendall similarity comparison between rankings

## Repository Structure
- notebooks/ → Jupyter notebooks for experiments
- src/ → Core Python implementation
- data/ → Datasets used in experiments

## Reproducibility
All results presented in the paper can be reproduced using the provided notebooks and scripts.

## License
MIT License

## Important Note
Control examples and datasets used in this repository remain under the original licenses specified by their respective authors and sources.

## References
- Podinovskiy, V.V. (2022). Multicriteria Decision Making: Theory and Methods. Springer.
