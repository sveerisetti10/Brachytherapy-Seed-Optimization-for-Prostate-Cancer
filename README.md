
# Brachytherapy Seed Optimization for Prostate Cancer

## Introduction

This repository contains a Python-based optimization model developed for a case study in brachytherapy for prostate cancer treatment. The project, inspired by research at the Memorial Sloan-Kettering Cancer Center, utilizes Pyomo, an advanced optimization tool, to strategically place radioactive seeds in the prostate to maximize tumor exposure while safeguarding healthy tissue.

## Project Background

The model addresses a critical question in radiation therapy: How to optimally place a limited number of radioactive seeds to ensure effective tumor treatment with minimal harm to surrounding healthy tissues? The code specifically addresses question 3c from the provided case study, set in a 16-section prostate treatment grid.

## Model Specifications

Objective: To minimize exposure of healthy tissue while ensuring each tumor section receives at least 3 units of exposure.
Solution Strategy: The model uses an optimization algorithm to determine the best positions for three seeds within the grid, taking into account the unique geometry and requirements of prostate cancer treatment.
Techniques Used: Implements constraint programming and Euclidean distance calculations within Pyomo's environment to solve the optimization problem.

## Installation and Setup

Dependencies: Python, Pyomo, numpy, pandas, and a suitable solver (e.g., 'ipopt').
Running the Code: After installing the dependencies, the script can be executed in any Python environment.

## Usage

Input: The model requires grid information regarding the location of healthy and tumor tissues.
Execution: Run the script to generate the optimal seed positions based on the defined constraints and objective function.
Output: The solution provides the coordinates for seed placement, minimizing radiation exposure to healthy tissues.

## Potential Applications

This model, while developed for a specific case study, can be adapted for broader applications in radiation therapy and treatment planning in oncology, demonstrating the power of optimization in medical decision-making.

## Contributions

Contributions to enhance the algorithm, improve computational efficiency, or adapt the model for other medical applications are highly encouraged.

