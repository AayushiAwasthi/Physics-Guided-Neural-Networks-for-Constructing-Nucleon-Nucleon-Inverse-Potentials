This repository implements a Physics-Guided Neural Network (PGNN) framework for constructing nucleon-nucleon (NN) inverse potentials using inverse scattering theory.
The framework integrates the Phase Function Method (PFM) with a two-stage supervised MLP model to predict the Malfliet-Tjon (MT) potential parameters from sparse phase-shift data.

We propose a PGNN framework for constructing NN inverse potentials based on inverse scattering theory.

Uses the Phase Function Method (PFM) + two-stage MLP model.

Generates a synthetic phase-shift dataset by solving the phase equation for ℓ = 0 using the 5th-order Runge-Kutta method.

First neural network predicts attractive strength (Ṽ_A).

Second predicts repulsive strength (Ṽ_R).

Range parameter (μ) is obtained via error minimization.

Validated for n-p, p-p, and n-n scattering in the ¹S₀ state.

Achieves accurate phase shifts and corresponding NN potentials.
