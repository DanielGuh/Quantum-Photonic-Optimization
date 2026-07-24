# Quantum Photonic Analysis & Fundamental Constant Optimization

## Project Overview
This repository contains the computational analytics pipeline and regression frameworks used to model the Photoelectric Effect across variable LED light wavelengths. The core objective is executing linear optimizations to extract quantum fundamental parameters (Planck's Constant, Work Function) and modeling physical space charge anomalies.

## Repository Assets
* `PhotoelectricEffectData - Exercise 1.csv` & `Exercise 2.csv`: Raw instrumentation datasets capturing threshold stopping voltages and photocurrent variances.
* `PhotoelectricEffectAnalysis.py`: The operational Python script mapping threshold frequencies and calculating regression metrics using `scipy.optimize.curve_fit`.
* `Photoelectric Effect Report.pdf`: The technical physics paper containing error propagation matrices and hardware constraint analysis.

## Technical Execution
* **Multi-Variable Modeling:** Structured statistical arrays parsing phototube stopping voltages across an emission frequency span of 450 THz to 760 THz.
* **Optimization Diagnostics:** Evaluated extreme parameter variances (Reduced Chi-Squared analysis) to isolate systemic instrumentation error from theoretical ideal models.
* **Nonlinear Analysis:** Processed photocurrent intensity limits to isolate space charge degradation curves using custom exponential fitting.
