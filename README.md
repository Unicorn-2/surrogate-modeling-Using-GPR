# surrogate-modeling-Using-GPR
Kriging (Gaussian Process Regression) based surrogate model for predicting damper blade deformation from thickness variations.


# Economizer Damper Blade Surrogate Modeling

## Project Overview

This project develops a surrogate model for predicting deformation in economizer damper blades based on design thickness parameters.

The objective was to reduce computational cost associated with repeated finite element simulations by developing a fast and accurate predictive model.

## Problem Statement

Finite Element Analysis (FEA) provides accurate deformation predictions but can be computationally expensive when evaluating multiple design configurations.

A surrogate model was developed to approximate FEA results and enable rapid design evaluation.

## Methodology

1. Generate simulation data from design studies.
2. Extract thickness and deformation responses.
3. Train a Kriging (Gaussian Process Regression) model.
4. Validate surrogate predictions against simulation results.
5. Evaluate prediction accuracy.

## Tools & Technologies

- Python
- NumPy
- Pandas
- Scikit-Learn
- Gaussian Process Regression (Kriging)
- ANSYS Mechanical
- Data Visualization

## Inputs

- Damper blade thickness parameters
- FEA simulation results

## Outputs

- Predicted blade deformation
- Response surface visualization
- Model performance metrics

## Key Benefits

- Reduced simulation time
- Faster design iterations
- Improved engineering decision-making
- Support for design optimization studies

## Author

Sidharudha Metri

Mechanical Engineer | M.Tech in AI & Machine Learning
