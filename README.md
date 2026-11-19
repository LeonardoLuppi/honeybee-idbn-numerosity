# A Deep Belief Network Approach to Numerical Cognition in *Apis mellifera*

Code, synthetic stimulus generation pipeline, and statistical analysis for the B.Sc. thesis:
*"A Deep Belief Network Approach to Numerical Cognition in Apis mellifera: Modeling Visual Processing Under Biological Constraints"* (University of Padua, A.Y. 2025/2026).

## Contents
- `honeybee_idbn_simulation.ipynb` — Complete reproducible pipeline:
  - 2D-DFT biological low-pass optical filter and 41×41 binocular ommatidial sampling
  - Unsupervised iterative Deep Belief Network (iDBN) training across 10 independent networks
  - Dual delta-rule linear readout conditioning ("greater-than" and "less-than" cohorts)
  - Spectral diagnostics, edge-disrupted control tests, rule extrapolation, and zero-set evaluation

## How to Run
Click the **Open in Colab** badge at the top of the notebook and select **Runtime → Run all**. All stimuli are generated programmatically with fixed random seeds for reproducibility.
