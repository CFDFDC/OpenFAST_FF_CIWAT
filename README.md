# FAST.Farm_CIWAT

A fork of NREL OpenFAST, with the FAST.Farm model being modifed to enhance the prediction of dynamic wake evolution.

Key features
- Incorporating convective instabilities (CI) mechanism in wake-added turbulence (WAT) calculation to predict turbulent kinetic energy generation
- Accounting for scale dependency of large-scale meandering motions to improve the prediction of mean wake expansion and wake meandering 

Code modifications (please navigate with CIWAT flag)
- modules/wakedynamics/src/WakeDynamics.f90
- modules/awae/src/AWAE.f90

For the model development and assessment, please refer to https://doi.org/10.1016/j.energy.2023.130167.
