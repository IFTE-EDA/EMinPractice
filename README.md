# EMinPractice
Simulation scripts and data

We provide the following scripts:

- FEM_APDL: Used for MTTF data generation and verification of our RC SPICE results. Can be run in Ansys.
- RC_SPICE: Our Spice script for the example circuit.
- Interpolate.py: Adds noise and finds matarial parameters from MTTF data.

Extending the results shown in our paper, we provide:
- MTTF_Data: Original FEM lifetime simulation results that we then use to find material parameters.
- FEM_Stress_Data, FEM_Stress_Data_reference, FEM_Stress_Data_reservoir: Extending FEM results shown in Fig. 6 (obtained with script FEM_APDL).

